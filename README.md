# Health Insurance Premium Prediction

Welcome to the **Health Insurance Premium Prediction System** — a complete machine learning solution designed to predict annual health insurance premiums based on personal and health-related attributes. This project integrates **data cleaning**, **feature engineering**, **model training**, and a **Streamlit application** for intuitive predictions.

---

## Project Structure

```
ml-health-insurance-premium-prediction/
├── App/                     # Streamlit frontend application
├── artifacts/               # Trained ML models and scalers
├── data_segmentation.py     # Script for data segmentation
├── insuranc_premium_overall.py  # Main pipeline for overall premium prediction
├── premium_young.py         # Pipeline for young demographics
├── premium_young_with_gr.py # Pipeline with genetical risk
├── primium_rest.py          # Pipeline for remaining demographics
├── primium_rest_with_gr.py  # Pipeline with genetical risk
├── premiums.xlsx            # Full dataset
├── premiums_rest.xlsx       # Segmented dataset
├── premiums_young.xlsx      # Segmented dataset
├── premiums_young_with_gr.xlsx # Segmented dataset with genetical risk
├── requirements.txt         # Python dependencies
└── README.md                # Project overview and setup instructions
```

---

## Features

✅ **Comprehensive Data Cleaning**: Handles missing values, outliers, and inconsistent categories
✅ **Feature Engineering**: Encoding categorical variables, scaling numeric columns, and calculating risk scores
✅ **Multiple Models**: Linear Regression, Ridge Regression, and XGBoost for robust predictions
✅ **Streamlit Frontend**: User-friendly web app for insurance premium prediction
✅ **Modular Pipeline**: Organized codebase for scalability and maintenance

---

## Getting Started

Follow these steps to get up and running:

### 1. Clone the Repository

```bash
git clone https://github.com/An1sh-D/ml-health-insurance-premium-prediction.git
cd ml-health-insurance-premium-prediction
```

---

### 2. Install Dependencies

Ensure you have **Python 3.9+** installed, then install required packages:

```bash
pip install -r requirements.txt
```

---

### 3. Run Data Processing Pipelines

Run any of the processing scripts based on your needs. For example:

```bash
python insuranc_premium_overall.py
```

---

### 4. Launch the Streamlit Application

Navigate to the `App` directory (if your main Streamlit script is there) or project root and run:

```bash
streamlit run App/main.py
```

> The Streamlit app will open automatically in your default web browser.

---

## Testing

Basic functional tests are embedded within scripts (e.g. shape checks, prints). For extending this project with **pytest unit tests**, create a `tests/` directory and include pipeline, preprocessing, and model tests.

---

## Contributing

We welcome contributions to improve the **Health Insurance Premium Prediction System**. If you would like to contribute:

1. Fork this repository.

2. Create a feature branch:

   ```bash
   git checkout -b feature-name
   ```

3. Commit your changes:

   ```bash
   git commit -m 'Add some feature'
   ```

4. Push to the branch:

   ```bash
   git push origin feature-name
   ```

5. Open a pull request.

---

## License

This project is licensed under the **MIT License**. For details, please refer to the `LICENSE` file.

---

> Thank you for using the Health Insurance Premium Prediction System! 🎯 Enhance your data-driven decisions with confidence.

---
