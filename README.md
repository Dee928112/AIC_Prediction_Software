# AIC-Prediction Software

This software is developed for predicting and interpreting the mechanical strength and thermal conductivity of aerogel-incorporated concrete (AIC) based on trained machine learning models.

The software provides an easy-to-use graphical user interface (GUI) for predicting the compressive strength, flexural strength, and thermal conductivity of AIC, and interpreting the prediction results using SHAP-based explanation methods.

---

## Download

Please download `AIC_Prediction.zip` from the Releases section.

---

## Software functions

The software includes two main functions:

### 1. Performance prediction module

The software predicts:

- Compressive strength
- Flexural strength
- Thermal conductivity

using trained machine learning models.

### 2. Prediction interpretation module

The software provides SHAP-based waterfall plots to explain the contribution of input features to each prediction result.

Red bars indicate features that increase the predicted value, while blue bars indicate features that decrease the predicted value.

---

## How to use

1. Download `AIC_Prediction.zip` from the Releases section.

2. Unzip the file.

3. Open the `AIC_Prediction` folder.

4. Double-click `AIC_Prediction.exe` to launch the software.

5. Input the mixture parameters.

6. Click the "Predict" button to obtain the predicted results.

7. The SHAP-based explanation plots will be generated automatically.

---

## Software workflow

The overall workflow of the software is:

Input mixture parameters

↓

Input range checking

↓

Data preprocessing and normalization

↓

Machine learning model prediction

↓

SHAP-based prediction explanation

↓

Output results

---

## Important notes

Please do not delete or move the `_internal` folder, `outputs` folder, or `.pkl` files. These files are required for the software to run.

The `.pkl` files contain the trained machine learning models and normalization parameters. If the models are updated, replace the corresponding `.pkl` files with the same filenames.

The software may briefly display a console window during SHAP explanation generation. This does not affect the prediction results.

---

## Source code

The source code and trained model files are available in this repository.
