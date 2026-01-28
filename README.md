# Heart Stroke Prediction by Sanchit

A machine learning-powered web application that predicts the risk of heart stroke based on various medical and lifestyle parameters.

## Overview

This application uses a trained machine learning model to assess heart stroke risk by analyzing multiple health indicators including age, blood pressure, cholesterol levels, ECG results, and other cardiovascular risk factors.

## Features

- **User-Friendly Interface**: Clean, dark-themed UI for easy data input
- **Comprehensive Risk Assessment**: Evaluates multiple cardiovascular risk factors
- **Real-Time Prediction**: Instant risk assessment based on input parameters
- **Medical Parameter Validation**: Ensures data integrity for accurate predictions

## Input Parameters

The application collects the following information:

### Demographic Information
- **Age**: Patient's age (adjustable slider)
- **Sex**: Male (M) or Female (F)

### Cardiovascular Indicators
- **Chest Pain Type**: 
  - ATA (Atypical Angina)
  - NAP (Non-Anginal Pain)
  - ASY (Asymptomatic)
  - TA (Typical Angina)

### Vital Signs & Lab Results
- **Resting Blood Pressure**: Measured in mm Hg
- **Cholesterol**: Serum cholesterol in mg/dL
- **Fasting Blood Sugar**: Binary indicator (>120 mg/dL or not)
- **Resting ECG**: Normal, ST-T wave abnormality, or Left Ventricular Hypertrophy

### Exercise & Cardiac Stress Indicators
- **Max Heart Rate**: Maximum heart rate achieved
- **Exercise-Induced Angina**: Yes (Y) or No (N)
- **Oldpeak (ST Depression)**: ST depression induced by exercise relative to rest
- **ST Slope**: Upsloping, Flat, or Downsloping

## Installation

```bash
# Clone the repository
git clone https://github.com/sanchit/heart-stroke-prediction.git
cd heart-stroke-prediction

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

## Usage

1. Open the application in your web browser
2. Fill in all required medical parameters:
   - Adjust sliders for Age, Max Heart Rate, and Oldpeak
   - Select appropriate values from dropdown menus
   - Enter numeric values for Blood Pressure and Cholesterol
3. Click the "Predict" button
4. View your heart stroke risk assessment

## Model Information

The prediction model has been trained on cardiovascular disease datasets and considers multiple risk factors including:
- Patient demographics
- Clinical measurements
- Exercise test results
- ECG findings

**Note**: This tool is for educational and informational purposes only. It should not replace professional medical advice, diagnosis, or treatment.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Future Enhancements

- [ ] Add detailed risk analysis breakdown
- [ ] Include lifestyle recommendations based on risk factors
- [ ] Multi-language support
- [ ] Export prediction results as PDF
- [ ] Historical tracking of risk assessments
- [ ] Integration with wearable device data



**Disclaimer**: This is a demonstration project for educational purposes. Medical decisions should always be made in consultation with qualified healthcare providers.
