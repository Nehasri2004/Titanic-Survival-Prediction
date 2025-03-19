Titanic Survival Prediction:
This project builds a machine learning model to predict whether a passenger survived the Titanic disaster. It includes data preprocessing, feature engineering, model training, and evaluation.

📂 Project Structure

titanic-survival-prediction/
│── data/                   # Dataset files (train.csv, test.csv)
│── notebooks/              # Jupyter Notebooks for EDA and model experiments
│── src/                    # Python scripts for preprocessing & modeling
│   │── preprocess.py       # Data preprocessing functions
│   │── train.py            # Training the model
│   │── evaluate.py         # Model evaluation
│── models/                 # Saved models
│── results/                # Performance metrics, confusion matrix
│── README.md               # Project overview, setup, and usage instructions
│── requirements.txt        # Dependencies
│── main.py                 # Main script for training & testing
│── titanic_survival_model.pkl  # Saved trained model
│── .gitignore              # Files to ignore (virtual environment, cache, etc.)
```
Dataset Information
- The dataset contains details of Titanic passengers:
  - **Features**: Age, Gender, Ticket Class, Fare, Embarkation Port, etc.
  - **Target Variable**: `Survived` (0 = No, 1 = Yes)
- Missing values are handled, categorical features are encoded, and numerical features are normalized.

 Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```bash
   python main.py
   ```
Model Training & Evaluation
- Model Used: Random Forest Classifier
- Performance Metrics:
  - Accuracy: 85%
  - Precision, Recall, F1-Score included in `results/`
- The trained model is saved as titanic_survival_model.pkl

Results & Visualizations
- Below is the confusion matrix from model evaluation:


