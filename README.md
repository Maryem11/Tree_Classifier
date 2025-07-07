# 🌾 Optimal Crop Planting Location (Decision Tree Model)

This project uses machine learning to recommend the ideal crop to plant based on environmental conditions. It applies classification techniques to support data-driven decisions in agriculture, helping optimize crop selection by analyzing soil and climate features.

## 📌 Objective

Predict the most suitable crop for a given location using key environmental parameters such as:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall

## 🧪 Dataset

- Source: Public agricultural dataset (collected via open-source platforms [🔗 View source](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)).
- Includes 1,600+ observations across 22 crop types.

## 🔍 Key Steps

1. **Data Loading & Exploration**  
   - Understand feature distributions  
   - Check for missing values  

2. **Preprocessing**  
   - Feature scaling (StandardScaler)  
   - Label encoding (target variable)

3. **Model Training**  
   - **Decision Tree Classifier** (main model)  
   - Accuracy evaluation on train/test split  

4. **Visualization**  
   - Feature importance  
   - Decision tree plot  

## 📈 Results

- Decision Tree model achieved high accuracy on both training and testing sets.
- Feature importance revealed key drivers like rainfall, pH, and nitrogen.

## 🛠 Tools & Technologies

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Google Colab

## 📁 File Structure

- `Crops_Ideal_Location.ipynb`: Main notebook
- `dataset_crops.csv`: Dataset file (stored in Google Drive)

## 🚀 Use Case

Useful for data scientists, agronomists, or organizations seeking to apply ML in agriculture for efficient crop planning and decision support.
