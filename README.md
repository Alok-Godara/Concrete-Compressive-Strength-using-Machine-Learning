# 🧱 Smart Infrastructure: Predicting Concrete Compressive Strength using Machine Learning

This project uses machine learning to predict the **compressive strength of concrete** based on its ingredients. The model assists in optimizing mix designs, reducing material waste, and enhancing structural reliability.

## 📂 Dataset

The dataset used is the **Concrete Compressive Strength Dataset** from the UCI Machine Learning Repository. It includes 1030 samples with the following features:

- Cement (kg/m³)
- Blast Furnace Slag (kg/m³)
- Fly Ash (kg/m³)
- Water (kg/m³)
- Superplasticizer (kg/m³)
- Coarse Aggregate (kg/m³)
- Fine Aggregate (kg/m³)
- Age (days)
- **Target:** Concrete Compressive Strength (MPa)

## 🧠 Model

A simple feedforward neural network (Multilayer Perceptron) is used to learn and predict the target variable.

### 🔧 Libraries Used
- `pandas`, `numpy`
- `sklearn` for preprocessing and splitting
- `tensorflow` and `keras` for building and training the neural network
- `matplotlib` for visualization

## 📊 Evaluation

- **Loss function**: Mean Squared Error (MSE)
- **Performance Metric**: R² Score

The model shows promising accuracy in learning the non-linear relationship between ingredient proportions and concrete strength.

## 📈 Results

The model is trained over 100 epochs. Plots of loss curves and predictions versus actual values are included in the code.

## 📁 Files

- `Concrete_Data.xls`: Raw dataset
- `smart_infra_project.py`: Model building, training, and evaluation code
- `Smart_Infra_Project.pdf`: Project report with background, methodology, and conclusions

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/smart-infra-concrete-strength.git
   cd smart-infra-concrete-strength
