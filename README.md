# 🗑️ RealWaste Image Classification using Deep Learning

## 📌 Overview

Accurate waste classification is crucial for effective waste management and reducing environmental damage. This project uses deep learning techniques to classify real-world waste images into categories such as glass, plastic, metal, and cardboard.

---

## 🎯 Objective

To develop and compare the performance of four deep learning models on the **RealWaste** dataset, enabling automatic classification of waste images and improving waste management practices.

---

## 🗃️ Dataset: RealWaste
- [🔗 RealWaste Dataset - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/908/realwaste)
- 🏷️ 4,752 labeled images  
- 🏞️ Captured from Whyte’s Gully Waste & Resource Recovery Centre in Wollongong, Australia  
- 🧾 Categories: Glass, Metal, Plastic, Cardboard, etc.  
- 🖼️ Image size: 524x524 px  

---

## 🧠 Deep Learning Models Used

| Model         | Architecture Type    |
|---------------|-----------------------|
| MobileNetV3   | Lightweight CNN       |
| ResNet152     | Residual Network      |
| DenseNet121   | Densely Connected CNN |
| ConvNeXt      | Transformer-inspired CNN |

---

## 🛠️ Methodology

- ✅ **KDD Approach**: Data collection → Preprocessing → Training → Evaluation  
- 🧼 Preprocessing: Image resizing, normalization, augmentation  
- 🧠 Training: Using TensorFlow/Keras with transfer learning  
- 📈 Evaluation: Accuracy, precision, recall, confusion matrix  

---

## 📊 Results Summary

| Model        | Accuracy |
|--------------|----------|
| MobileNetV3  | 85%+     |
| ResNet152    | 85%+     |
| DenseNet121  | 95%+     |
| ConvNeXt     | 95%+     |

✅ **DenseNet121** and **ConvNeXt** performed the best in real waste classification.

---

## 📸 Sample Classes

>   Cardboard, Paper, Plastic, Textile Trash,
 Food Organics, Vegetation, Glass, Metal, and Miscellaneous
 Trash
> 
![sample waste data 9](https://github.com/user-attachments/assets/137e7e32-ff0a-44ba-82b6-d13764f0c645)

---

## 🚧 Limitations

- Some models struggle with irregularly shaped or contaminated waste.
- Prediction accuracy drops if image quality is poor.

---

## 🔮 Future Scope

- Improve detection on mixed or deformed waste.
- Explore real-time classification using embedded systems (e.g., Raspberry Pi).
- Integrate with smart bins for real-world applications.

---

## 👨‍💻 Authors

- **Debayan Biswas** – [@deba033](https://github.com/deba033)
- **Ishita Kundu** - [@IshitaK834](https://github.com/IshitaK834)
- **Pinaki Pani** - [@PRPRIESLER](https://github.com/PRPRIESLER)
- **Yash Bhargava** 

---

## 📄 License

This project is for academic and research use. You may modify and use with appropriate credit.
