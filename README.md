# 🚭 Smoker Detection Dataset

![Smoking vs. Non-Smoking](https://cdn-icons-png.flaticon.com/512/709/709496.png)

## 📘 About the Dataset

The **Smoker Detection Dataset** contains **1,120 high-quality images** equally divided into **two classes**:

| Class | Number of Images |
|:------|:----------------:|
| **Smoking (Smokers)** | 560 |
| **NotSmoking (Non-Smokers)** | 560 |

All images are preprocessed and resized to a consistent resolution of **250 × 250 pixels**.

---

## 📂 Dataset Structure
Smoker_Detection_Dataset/
│
├── Smoking/
│ ├── image_001.jpg
│ ├── image_002.jpg
│ └── ...
│
└── NotSmoking/
├── image_001.jpg
├── image_002.jpg
└── ...

---

## 🌿 Data Collection and Curation

The dataset was curated by scanning through various **search engines** using diverse keywords such as:

> *“cigarette smoking”, “smoker”, “person coughing”, “taking inhaler”, “person on the phone”, “drinking water”*, and others.

This approach ensures diversity and realism in both classes.

To enhance the dataset’s robustness, we deliberately introduced **inter-class confusion** by including visually similar but semantically different images. For example:

- **Smoking Class:**  
  Includes images of smokers from multiple angles, lighting conditions, and gestures (e.g., holding a cigarette, exhaling smoke, lighting up).

- **NotSmoking Class:**  
  Includes people **mimicking similar gestures** but not smoking — e.g., drinking water, holding a phone, coughing, or using an inhaler.

This variation helps train deep learning models to differentiate subtle visual cues, improving generalization.

---

## 🧠 Research Motivation

This dataset was designed to support **deep learning research** in:

- Automated smoker detection systems  
- Environmental surveillance  
- Smart city monitoring  
- Public health analytics and safety enforcement  

By accurately identifying smokers in real-time video or image feeds, this dataset contributes to **green environment initiatives** and **urban safety automation**.

---

## 🧩 Dataset Split

| Subset | Percentage | Purpose |
|:--------|:------------:|:---------|
| **Training + Validation** | 80% | Model training and hyperparameter tuning |
| **Testing** | 20% | Final model evaluation |

---

## ⚙️ Image Preprocessing

All images were:
- Manually reviewed and filtered for quality  
- Center-cropped or scaled to **250×250 px**  
- Stored in RGB format  
- Maintained with natural backgrounds for realism  

---

