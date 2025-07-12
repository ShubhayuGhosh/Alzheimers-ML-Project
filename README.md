# Alzheimers-ML-Project
Predicting and Classifying alzheimer's disease using biomarkers


# Project: Alzheimer's Disease Classification (ML)

This project aims to build an interpretable, multimodal ML pipeline for predicting when cognitively normal or mildly impaired individuals will convert to Alzheimer’s Disease (AD), using real-world longitudinal cohort data (NACC, ADNI). We combine clinical, MRI-based, and genetic features to model time-to-conversion, focusing on transparent methods that support both publication and clinical deployment.

# Goal:
	•	Build and benchmark survival models (e.g., Cox Proportional Hazards, Random Survival Forest, XGBoost Survival) to predict conversion from CN/MCI to AD.
	•	Integrate explainability tools like SHAP to provide model transparency at individual and group levels.
	•	Evaluate models on external cohorts to ensure generalizability.
	•	Prototype a clinician-friendly Streamlit dashboard to visualize patient risk and feature contributions.
	•	Contribute toward a publishable, reproducible ML workflow with real translational potential.


# Setup

1. Clone the repo
git clone https://github.com/ShubhayuGhosh/Alzheimers-ML-Project.git

2. Install Python dependencies
pip install -r requirements.txt

3.	Prepare the dataset
	•	Request and download NACC or ADNI data (not hosted here due to license).
	•	Use our data/cleaning/ scripts to transform raw tables into features.csv.

4.	Run Notebooks

# Contributing

We welcome contributions, especially from those passionate about medical ML or longitudinal modeling.
	1.	Fork the repo and create a feature branch
	2.	Work on specific tasks (feature engineering, modeling, dashboard)
	3.	Document your changes & include a “Failure Log” comment block if needed
	4.	Submit a Pull Request using our template

📄 See CONTRIBUTING.md for detailed collaboration guidelines

# License
This project is licensed under the MIT License.

# Contact
For questions or collaboration proposals, reach out to:
Shubhayu Ghosh → shubhayughosh10@gmail.com
Or open a GitHub issue.


