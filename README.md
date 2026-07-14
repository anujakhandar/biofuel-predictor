# 🌱 Biofuel Energy Potential Predictor

Biofuel Energy Potential Predictor is a machine learning web application that estimates the biofuel energy potential from agricultural crop residues across India. The application enables users to analyze crop production data, predict energy generation, and visualize biomass availability through interactive dashboards.

---

## 🚀 Features

- 🌾 Predict biofuel energy potential from agricultural crop residues
- 🤖 Machine Learning-based prediction using Random Forest Regression
- 📊 Interactive data visualizations and analytics dashboard
- 🗺️ Choropleth map for state-wise biofuel potential across India
- 📈 Crop-wise and state-wise production analysis
- 🎯 Real-time prediction through a user-friendly Streamlit interface
- 📁 Dataset preprocessing and missing value handling

---

## 🛠️ Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### Machine Learning
- Random Forest Regressor
- Artificial Neural Network (ANN)

### Data Processing
- Pandas
- NumPy

### Visualization
- Plotly
- Matplotlib

### Model Persistence
- Joblib

---

## 📂 Project Structure

```text
Biofuel-Energy-Predictor/
│
├── app.py
├── model.pkl
├── crop_production.csv
├── india_states.geojson
├── requirements.txt
├── README.md
│
├── notebooks/
│   └── model_training.ipynb
│
└── assets/
```

---

## ⚙️ Project Workflow

```text
Crop Production Dataset
          │
          ▼
 Data Cleaning & Preprocessing
          │
          ▼
 Feature Engineering
          │
          ▼
 Random Forest Model Training
          │
          ▼
 Model Evaluation
          │
          ▼
 Model Serialization (Joblib)
          │
          ▼
 Streamlit Application
          │
          ▼
 Energy Prediction & Visualization
```

---

## 📊 Dataset

The model uses agricultural crop production data containing:

- State
- District
- Crop
- Season
- Area
- Production
- Crop Yield

The dataset is preprocessed by:

- Handling missing values
- Removing inconsistencies
- Feature encoding
- Data normalization

---

## 🤖 Machine Learning Pipeline

1. Load agricultural crop production dataset.
2. Perform data cleaning and preprocessing.
3. Extract relevant features for prediction.
4. Train a Random Forest Regression model.
5. Evaluate model performance.
6. Save the trained model using Joblib.
7. Deploy the model through a Streamlit web application.
8. Predict biofuel energy potential from user inputs.

---

## 📈 Visualizations

The application includes:

- State-wise biofuel potential map
- Crop production analysis
- Distribution charts
- Feature importance visualization
- Energy prediction dashboard
- Interactive graphs using Plotly

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Biofuel-Energy-Predictor.git

cd Biofuel-Energy-Predictor
```

---

### Create Virtual Environment

```bash
python -m venv .venv
```

Windows

```bash
.venv\Scripts\activate
```

Linux / macOS

```bash
source .venv/bin/activate
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Run the Application

```bash
streamlit run app.py
```

---

## 📖 Example Workflow

1. Launch the Streamlit application.
2. Enter crop and production details.
3. The trained Random Forest model predicts biofuel energy potential.
4. Explore interactive charts and state-wise visualizations.
5. Compare energy potential across different crops and regions.

---

## 📊 Model Performance

- Machine Learning Algorithm: Random Forest Regression
- Deep Learning Model: Artificial Neural Network (ANN)
- Model Accuracy: **~89%**
- Evaluation Metrics:
  - R² Score
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

---

## 🔮 Future Enhancements

- Support for additional biomass sources
- Weather and climate data integration
- Time-series forecasting
- Carbon emission estimation
- Recommendation system for optimal biofuel crops
- Cloud deployment



## 👩‍💻 Author

**Anuja Khandar**

