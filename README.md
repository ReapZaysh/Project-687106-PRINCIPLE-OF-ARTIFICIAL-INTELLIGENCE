# Flower Species Classification: CNN Model Comparison

## 📋 Project Overview
This project evaluates three Deep Learning architectures (**ResNet50, DenseNet121, and MobileNetV3**) to classify 5 types of flowers. We followed a team-based pipeline:

- **Data Engineer**: Dataset collection, standardization ($224 \times 224$), and GPU optimization.
- **Data Scientist**: Transfer Learning implementation and training for 50 epochs.
- **Data Analyst**: Performance visualization, mAP calculation, and error analysis.

## 📊 Dataset
The dataset is the **TensorFlow Flower Photos** collection (3,670 images).
- **Classes**: Daisy, Dandelion, Roses, Sunflowers, Tulips.
- **Access**: The data is downloaded automatically via the notebook script.

## 🏆 Final Results
| Model        | Accuracy | mAP    | Time (s) | Params |
|--------------|----------|--------|----------|--------|
| **MobileNetV3** | **90.6%** | **0.904** | **89s** | **0.9M** |
| ResNet50     | 90.2%    | 0.901  | 465s     | 23.5M  |
| DenseNet121  | 74.9%    | 0.752  | 461s     | 7.0M   |

**Conclusion**: MobileNetV3 is the best-suited model for this task due to its high accuracy and extreme efficiency.
