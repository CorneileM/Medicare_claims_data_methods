# Working with CMS's synthetic Medicare claims datasets
## From ETL to data analysis

Medical claims data are a vital source of real world evidence in healtcare, providing snapshots of medical events (e.g., diagnoses and disease staging, inpatient and outpatient procedures, medication prescribed, etc.) in real patients and their associated data (e.g., age, gender-assigned-at-birth, race, geographc location, etc.). Unlike data from clinical trials and controlled experiments, where patients are carefully selected and conditions tightly controlled, claims data offers a view into the healthcare practices in the messiness of the real world. For example, a clinical trial would typically exclude patients that have comorbitities outside of the clinical trial's target disease. But, after clinical trails and FDA approval, in the real world, patients undergoing treatment may have a number of co-occuring diseases that could influence the efficacy of a treatment. Claims data can help us understand how treatments work in the real world, and how they are used in the real world.

Although data scientists typically have an abundance of data at their disposal, claims data can be particularly difficult to get a hold of. A search on Kaggle or Github for claims datasets will yield few results. This is due to two things: 1. Patient privacy -- claims data are understandably protected by HIPAA and other privacy laws to protect patient privacy, and 2. Cost -- claims data are incredibly valuable to most stakeholders in the healthcare industry (e.g., pharmaceutical companies that want to find out if their drug is more effective than the competition), and medical insurance companies and third-party data brokers charge market-related prices for access to these data. 

For aspiring, or even seasoned, data scientists, this cost-of-access can be a significant barrier to entry into the field of healthcare data science which relies so heavily on claims data. 

While real claims data is hard to come by, the Centers for Medicare and Medicaid Services (CMS) has made available a number of synthetic datasets that mimic the structure and content of real claims data, but do not contain any real patient data. These datasets are available in "sandbox mode" and can be used to develop and test algorithms, and to learn about the structure of claims data.

The goal of this repository is to provide a step-by-step guide to working with CMS's synthetic Medicare claims datasets. We will start with the ETL process, and then move on to data analysis. We hope that this guide will be useful to data scientists who are interested in gaining experience with claims data, but have otherwise struggled to get access to real claims data. The repository will consist of easy-to-follow Jupyter notebooks that will guide you through the process of working with CMS's synthetic Medicare claims datasets form ETL to data analysis and visualization.

## Overview of the repository

### Extract, Transform, Load (ETL) process
#### ETL Part 1: Loading data from the BCDA API
- [ETL_Part1 notebook](Notebooks\A_ETL\ETL_Part1.ipynb)
#### ETL Part 2: Getting data cloud and SQL-ready
- [ETL_Part2 notebook](Notebooks\A_ETL\ETL_part2.ipynb) *# coming soon*
#### ETL Part 3: Creating longitudinal datasets for analysis
- [ETL_Part3 notebook](Notebooks\A_ETL\ETL_part3.ipynb) *# coming soon*

### Data analysis
#### Data analysis Part 1: Exploratory data analysis
- [Data_analysis_Part1 notebook](Notebooks\B_Data_analysis\Data_analysis_Part1.ipynb) *# coming soon*
#### Data analysis Part 2: Building disease and treatment logic
- [Data_analysis_Part2 notebook](Notebooks\B_Data_analysis\Data_analysis_Part2.ipynb) *# coming soon*
#### Data analysis Part 3: Hypothesis testing (treatment comparison)
- [Data_analysis_Part3 notebook](Notebooks\B_Data_analysis\Data_analysis_Part3.ipynb) *# coming soon*
#### Data analysis Part 4: Tracking patient journeys
- [Data_analysis_Part4 notebook](Notebooks\B_Data_analysis\Data_analysis_Part4.ipynb) *# coming soon*

### Data visualization
#### Data visualization Part 1: Building descriptive stats dashboards
- [Data_visualization_Part1 notebook](Notebooks\C_Data_visualization\Data_visualization_Part1.ipynb) *# coming soon*
#### Data visualization Part 2: Mapping patient journeys
- [Data_visualization_Part2 notebook](Notebooks\C_Data_visualization\Data_visualization_Part2.ipynb) *# coming soon*

