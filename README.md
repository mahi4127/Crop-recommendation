# Crop Recommendation System

## Project Description
This project uses machine learning to recommend the most suitable crops to plant based on various environmental factors and soil properties. The system is designed to help farmers increase crop yield and optimize resource usage.

## Features
- Analysis of environmental conditions and soil characteristics.
- Prediction of suitable crops based on input data.
- Visualizations to display the correlation between variables and crop suitability.

## Installation

To run this project, you will need Python and several dependencies:

```bash
git clone https://github.com/mahi4127/Crop-recommendation.git
cd Crop-recommendation
pip install -r requirements.txt
```

## Usage

After installation, you can run the notebook `Crop Recommendation (1).ipynb`:

```bash
jupyter notebook 'Crop Recommendation (1).ipynb'
```

Inside the notebook, you can input the environmental data and soil properties to get crop recommendations.

## Results

### Accuracy Comparison
The models used in this project show the following accuracy:

- **Decision Tree**: 90%
- **Naive Bayes**: 99.09%
- **SVM (Support Vector Machine)**: 97.95%
- **Logistic Regression**: 95.23%
- **Random Forest (RF)**: 99.09%

![Accuracy Comparison](https://github.com/mahi4127/Crop-recommendation/assets/118770598/eeb3dc7e-8d34-4f23-9b9a-f41e178645b3)

### Example Predictions
- Input: `[104, 18, 30, 23.603016, 60.3, 6.7, 140.91]` (example environmental and soil parameters)
  - **Prediction**: Coffee
- Input: `[83, 45, 60, 28, 70.3, 7.0, 150.9]`
  - **Prediction**: Jute

These results demonstrate the effectiveness of our models in predicting the most suitable crops based on given data.
