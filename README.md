## 📊 Dataset Description
The project utilizes structured datasets to train and validate the cognitive load models:
* **`Train_data.gz`**: The primary compressed training dataset containing baseline physiological/textual features and their corresponding cognitive load classifications.
* **`val.csv`**: A dedicated validation set used to evaluate model accuracy and prevent overfitting during the training phase.

## 🧠 Methodology
1. **Data Preprocessing**: Raw text and speech data inputs are cleaned and normalized.
2. **Feature Extraction**: Key indicators of cognitive stress are extracted from the text/speech patterns.
3. **Model Training**: The processed `Train_data.gz` is fed into the classification model to learn complex patterns associated with varying levels of cognitive load.
4. **Validation & Testing**: The model's predictive performance is rigorously tested against the unseen `val.csv` dataset to ensure high accuracy and reliability.
