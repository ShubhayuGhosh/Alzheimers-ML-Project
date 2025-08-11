# Alzheimers-ML-Project
Alzheimer's disease — tabular prediction 


# Project: Alzheimer's Disease Classification (ML)

 Predict who will convert to Alzheimer’s disease within 3 years using multimodal clinical tabular data with transparent, reproducible ML
 
# Goal:
Build a compact, well-documented pipeline and notebook set that:

	•	Produces a reproducible baseline classifier for 3-year conversion to AD (binary classification).
	•	Focuses on non-leaky, clinically meaningful features so results generalize to independent cohorts (e.g., NIMHANS).
	•	Includes failure audits, interpretability (SHAP), and a small interactive dashboard for per-patient explanation. (Future scope)
	•	Contribute toward a publishable, reproducible ML workflow with real translational potential.


# Setup

1. Clone the repo
git clone https://github.com/ShubhayuGhosh/Alzheimers-ML-Project.git

2. Install Python dependencies
pip install -r requirements.txt

3.	Prepare the dataset
	•	Request and download NACC dataset (not hosted here due to license, read more below).

4.	Run Notebooks

# Data Availability

This project uses data from the NACC repository
These datasets contain sensitive participant information and are not publicly redistributable under the terms of their data use agreements.

What this repository includes:

Example synthetic datasets (data/synthetic/) generated to mimic the structure and statistical properties of the real data — no actual patient data is included.

Code for data preprocessing, model training, and evaluation.


What this repository does not include:

Any original or derived participant-level data from NACC

Any files that could directly or indirectly identify a study participant.


How to access the real data: Researchers must apply for access directly from the data custodians:

[Data Request Form](https://naccdata.org/requesting-data/data-request-process)


Once approved, place the downloaded files and follow the preprocessing instructions in the repository.


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


