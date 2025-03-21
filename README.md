# Disease Prediction Using Machine Learning

## Overview
This Streamlit application predicts the likelihood of various diseases using trained machine learning models. The diseases currently supported include:
- Diabetes
- Heart Disease
- Parkinson's Disease
- Lung Cancer
- Hypo-Thyroid

## Features
- User-friendly web interface using Streamlit
- Background image for enhanced UI aesthetics
- Disease selection through a dropdown menu
- Secure input fields for entering medical data
- Machine learning models for disease prediction
- Results displayed with a success message

## Installation
To run this application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/disease-prediction.git
   cd disease-prediction
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Required Dependencies
Ensure you have the following Python packages installed:
```bash
pip install streamlit pickle5 scikit-learn numpy pandas
```

## File Structure
```
medical-diagnosis/
│── Models/
│   ├── diabetes_model.sav
│   ├── heart_disease_model.sav
│   ├── parkinsons_model.sav
│   ├── lungs_disease_model.sav
│   ├── Thyroid_model.sav
│── app.py
│── requirements.txt
│── README.md
```

## Usage
1. Open the web application.
2. Select a disease from the dropdown menu.
3. Enter the required medical parameters.
4. Click on the **Test Result** button to get the prediction.

## Notes
- The model files (`.sav`) should be placed inside the `Models/` directory.
- Ensure that input values are within realistic medical ranges for accurate predictions.
- This tool is intended for educational purposes and should not be used for actual medical diagnosis.

## Author
- **Dumpa Revanth** - Developer

## License
This project is licensed under the MIT License.

