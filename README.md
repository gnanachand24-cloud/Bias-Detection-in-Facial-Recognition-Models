# Bias Detection in Facial Recognition Models

## Overview

This project investigates demographic bias in facial recognition systems using deep learning. Facial recognition models often perform differently across age, gender, and ethnic groups, raising concerns about fairness and ethical AI.

Using the **UTKFace dataset**, this project evaluates a facial recognition model and analyzes its performance across demographic groups to identify potential biases.

> **Goal:** Evaluate model fairness and highlight disparities in recognition performance across different populations.

---

## Features

* Facial image preprocessing
* Deep learning model for face recognition
* Performance evaluation
* Bias analysis across demographic groups
* Confusion matrix and classification report
* Fairness evaluation

---

## Technologies Used

* Python
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Dataset

**UTKFace Dataset**

The dataset contains facial images annotated with:

* Age
* Gender
* Ethnicity

These attributes are used to evaluate whether model performance varies across demographic groups.

---

## Workflow

1. Load the UTKFace dataset
2. Preprocess facial images
3. Train the deep learning model
4. Evaluate model performance
5. Compare accuracy across demographic groups
6. Analyze bias and fairness metrics

---

## Results

The project demonstrates how facial recognition systems may exhibit unequal performance across demographic groups and highlights the importance of fairness evaluation before deploying AI systems.

---

## Installation

```bash
git clone https://github.com/gnanachand24-cloud/Bias-Detection-in-Facial-Recognition-Models.git

cd Bias-Detection-in-Facial-Recognition-Models

pip install -r requirements.txt
```

---

## Future Improvements

* Train on larger balanced datasets
* Apply bias mitigation techniques
* Compare multiple deep learning architectures
* Evaluate additional fairness metrics

---

## Author

**Gnanachand**
