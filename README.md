# Pneumonia detection
## This project is about recognising pneumonia using X-ray lung images.

## What is Pneumonia?
Pneumonia is an inflammation of the lung tissue in which the small air sacs (alveoli) are primarily affected. The course of the disease can range from mild to severe. Risk factors include cystic fibrosis, chronic obstructive pulmonary disease (COPD), asthma, diabetes, heart failure, a previous smoking history, limited coughing ability (for example after a stroke) and a weakened immune system.


#### The diagnosis is usually based on:
* Clinical symptoms and physical examination
* Chest X-rays
* Blood tests
* Analysis of coughed-up mucus (sputum cultures)


## Description of Dataset
* Source: Kaggle - Chest X-Ray Images (Pneumonia) https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/data
* Patients: Pediatric patients from Guangzhou Women and Children's Medical Center.
* Total Images: 5,863
* Classes: PNEUMONIA, NORMAL
* Structure:
```
chest_xray/
├── train/
│   ├── NORMAL/
│   └── PNEUMONIA/
├── val/
│   ├── NORMAL/
│   └── PNEUMONIA/
└── test/
    ├── NORMAL/
    └── PNEUMONIA/
```

## Project Goals
* Development of an accurate image classification model for the detection of pneumonia
* Improve classification accuracy through data augmentation and class balancing.
* Use machine learning to enhance performance with limited data.



