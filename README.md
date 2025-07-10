Health Insurance Premium Prediction
Welcome to ml-health-insurance-premium-prediction — a machine learning project designed to predict health insurance costs based on customer demographics, medical history, and income data. This project implements end-to-end data cleaning, feature engineering, model training (Linear, Ridge, XGBoost Regression), and a Streamlit app for live deployment.

🔧 Project Structure
bash
Copy
Edit
ml-health-insurance-premium-prediction/
├── App/                        # Streamlit frontend application
├── artifacts/                  # Saved ML models and scalers
├── data_segmentation.py        # Script for splitting datasets
├── insuranc_premium_overall.py # Overall training and preprocessing
├── premium_young.py            # Young segment model training
├── premium_young_with_gr.py    # Young segment with genetical risk model training
├── primium_rest.py             # Rest segment model training
├── primium_rest_with_gr.py     # Rest segment with genetical risk model training
├── premiums.xlsx               # Full dataset (Excel)
├── premiums_rest.xlsx          # Segmented dataset for rest population
├── premiums_young.xlsx         # Segmented dataset for young population
├── premiums_young_with_gr.xlsx # Young dataset with genetical risk
└── README.md                   # Project overview and setup instructions
✨ Features
Comprehensive Data Cleaning: Missing values handling, outlier removal, invalid negative value corrections

Feature Engineering: Categorical encoding, medical risk score calculation, income segmentation

Regression Modeling: Linear Regression, Ridge Regression, and XGBoost Regression with hyperparameter tuning

Streamlit Frontend: Interactive application for real-time insurance premium predictions

Well-Structured Scripts: Segregated scripts for each dataset segment for clean reproducibility

🚀 Getting Started
Clone the Repository
bash
Copy
Edit
git clone https://github.com/An1sh-D/ml-health-insurance-premium-prediction.git
cd ml-health-insurance-premium-prediction
Install Dependencies
Ensure you have Python 3.10+ installed. Then install requirements:

bash
Copy
Edit
pip install -r requirements.txt
Run Training Scripts
Generate models and scalers for each segment by running:

bash
Copy
Edit
python premium_young.py
python primium_rest.py
Run other scripts similarly if you want to generate models for datasets with genetical risk integrated.

Launch the Streamlit Application
From the project root or inside App/:

bash
Copy
Edit
streamlit run main.py
The app will open in your default web browser for live predictions.

🔍 Testing
✅ Current testing is manual via Streamlit input validation and model evaluation scripts
🔜 Future updates can integrate unit tests for data pipelines and model performance

🤝 Contributing
Contributions are welcome to enhance this project further:

Fork this repository

Create a new branch: git checkout -b feature-name

Commit your changes: git commit -m 'Add feature'

Push to your branch: git push origin feature-name

Open a pull request

📜 License
This project is licensed under the MIT License. See LICENSE for details.
