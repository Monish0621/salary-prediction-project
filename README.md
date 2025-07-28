# ML Capstone Project: Expected CTC Prediction 🧠💼

This repository presents a complete Machine Learning pipeline to predict **Expected CTC (Cost to Company)**
based on professional, educational, and location-based attributes. 
The project demonstrates robust **EDA**, **data preprocessing**, **feature engineering**, and **model evaluation** 
using real-world-style HR data.

----------------------------------------------------------

## 🧩 Project Highlights

### 📌 Problem Statement
Can we accurately predict an individual's expected salary (CTC) based on their:
- Department, Designation, and Industry
- Graduation & Post-graduation details
- Skills, Ratings, and Offers in hand
- Current & Preferred location

### ⚙️ Key Processes
- **Missing Value Handling**:
  - Categorical: filled with `'Unknown'`
  - Numerical: filled with `mean`
- **One-hot Encoding** for categorical variables
- **Standardization** using `StandardScaler`

----------------------------------------------------------

## 📂 Files Included

- `launched1.ipynb`: Jupyter Notebook with complete EDA, preprocessing, model building, and evaluation.
- `expected_ctc.csv`: Input dataset containing anonymized candidate/job profile data.
- `requirements.txt`: List of dependencies (can be generated if needed).

-----------------------------------------------------------

## 📊 Visual Insights

- Distribution plots for numeric features
- Correlation heatmaps

------------------------------------------------------------

## 🛠️ Getting Started

To run this project locally:

```bash
# Step1: Clone this repository
git clone https://github.com/yourusername/ml-ctc-prediction.git
cd ml-ctc-prediction

# Step 2: Install dependencies
pip install -r requirements.txt

# Step 3: Launch the notebook
jupyter notebook launched1.ipynb
