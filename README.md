# Age and Gender Prediction Model Based on Text

This repository contains a machine learning model that predicts an author’s **age** and **gender** based solely on their written text.  
The project was developed as part of academic coursework for the **Computational Linguistics** class at **Lviv Polytechnic National University**.

---

## Overview

The system uses **two Random Forest models**:
- One model predicts **age**.
- The other predicts **gender**.

There are **two versions** of the age prediction model:
1. **Regression model** – predicts the author’s age as a numeric value.  
2. **Classification model** – predicts age as a category:
   - `0–20`
   - `21–30`
   - `30+`

> **Note:** The model tends to perform less accurately for the **30+** age category.

---

## Features

- Text preprocessing (tokenization, cleaning, vectorization)
- Independent Random Forest models for age and gender
- Support for both numerical and categorical age prediction
- Interactive section for testing predictions with custom text input

---

## Usage

At the end of the notebook (or script), you’ll find an **For User section** where you can type a sentence and see the model’s predictions for both **age** and **gender**.
input_text = "I just got back from my first year at university!"
predict(input_text)
