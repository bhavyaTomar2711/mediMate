# MediMate: AI-Driven Medical Recommendation System

## Project Overview
**MediMate** is an AI-powered medical recommendation system designed to assist users in diagnosing potential diseases based on input symptoms. By leveraging a machine learning model (SVM), MediMate predicts possible health conditions and provides additional information such as disease descriptions, medications, precautionary measures, workout routines, and diet plans.

## Features
- **Symptom-Based Disease Prediction**: Users input their symptoms, and MediMate predicts the most likely disease.
- **Detailed Disease Information**: For the predicted disease, the app provides:
  - Description
  - Medications
  - Precautions
  - Workout routines
  - Diet plans
- **User-Friendly Interface**: Simple and intuitive GUI using Tkinter for easy symptom input and detailed result display.

## Datasets
- **Training Dataset**: Includes symptom-based disease classification data used to train the SVM model.
- **Supplementary Datasets**:
  - Disease descriptions
  - Medications
  - Precautionary measures
  - Workout routines
  - Diet plans

## Technologies Used
- **Programming Language**: Python
- **Machine Learning**: Scikit-learn (SVM)
- **GUI Framework**: Tkinter
- **Data Manipulation**: Pandas, NumPy

## How It Works
1. The user enters symptoms separated by commas.
2. The system processes the symptoms, matches them with known symptom sets, and predicts the most probable disease.
3. MediMate displays the prediction along with relevant disease details:
   - Description
   - Medications
   - Precautions
   - Workout routines
   - Diet plans

## Getting Started

### Prerequisites
- Python 3.x
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `tkinter` (comes pre-installed with Python)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/medimate.git
## Install the Required Libraries:
```bash
pip install pandas numpy scikit-learn
