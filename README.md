MODEL PREDICT CHURN – TELEKOM

Project Description
-----------------------
Deep Learning project focused on predicting customer churn
in a telecommunications company (Telekom).

The objective is to identify customers at risk of leaving
the company using historical behavioral and demographic data.


Project Overview
-----------------------
Customer churn is one of the biggest challenges in the telecom industry.
Retaining customers is significantly cheaper than acquiring new ones.

This project builds a Neural Network model using TensorFlow/Keras to:

- Predict whether a customer will churn
- Analyze the most influential features
- Evaluate model performance using classification metrics
- Provide business insights for retention strategies


Technologies Used
-----------------------
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook


Project Workflow
-----------------------
1. Data Loading & Inspection
   - Dataset exploration
   - Data type verification
   - Initial distribution analysis

2. Data Cleaning & Preprocessing
   - Handling missing values
   - Encoding categorical variables
   - Feature engineering
   - Feature scaling
   - Train/Test split

3. Exploratory Data Analysis (EDA)
   - Churn distribution analysis
   - Customer satisfaction analysis
   - Contract type comparison
   - Correlation heatmap
   - Feature relationships

4. Model Development
   - Dense layer (ReLU activation)
   - Batch Normalization
   - Dense layer (ReLU activation)
   - Batch Normalization
   - Output layer (Sigmoid activation)

   Loss Function: Binary Crossentropy
   Optimizer: Adam

Evaluation Metrics
-----------------------
- Accuracy
- Precision
- Recall
- F1 Score
- AUC
- Confusion Matrix
- Precision-Recall curve
- Threshold optimization


Feature Importance
-----------------------
Permutation Importance was used to determine which
features most strongly influence churn prediction.

This provides insights into:
- Customer satisfaction impact
- Contract duration effects
- Usage behavior influence


Project Structure
-----------------------
Model-Predict-Churn-Telekom/
- Modelo_ML_churm_Telekom.ipynb
- README.md
- requirements.txt
- data/
   - telecomunicaciones.csv
   - California_DemographicsByCity_sample.csv


How to Run
-----------------------
1. Clone the repository:
   git clone https://github.com/xabiervc13/Model-Predict-Churn-Telekom.git

2. Install dependencies:
   pip install -r requirements.txt

3. Run Jupyter Notebook:
   jupyter notebook


Business Impact
-----------------------
This model helps telecom companies:
- Reduce customer churn
- Improve retention strategies
- Target high-risk customers
- Increase long-term revenue

Data
-----------------------
This project uses two datasets:

- clientes.csv → main customer dataset
- municipios.csv → municipalities dataset used for enrichment

Both datasets are located in the data/ folder.


Author
-----------------------
Xabier Vazquez Curiel
Machine Learning & Data Science Project
