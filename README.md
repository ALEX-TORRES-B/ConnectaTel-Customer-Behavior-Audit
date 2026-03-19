# ConnectaTel: Customer Behavior Audit & Strategic Segmentation

## Project Objective
This project performs a deep-dive data audit and behavioral analysis for **ConnectaTel**, a telecommunications provider. The goal is to identify data inconsistencies, analyze customer usage patterns across different generational cohorts, and uncover monetization opportunities through strategic segmentation.

## Datasets Used
The analysis integrates multiple data sources to create a 360-degree customer profile:
* **Users**: Demographic information (Age, City, Plan).
* **Calls**: Detailed logs of voice service interaction.
* **Messages**: Volume and character count of SMS services.
* **Plans**: Contractual limits and revenue structures.

## Analysis Phases
1. **Data Integrity Audit**: Identification and remediation of null values (MAR patterns) and systemic noise.
2. **Feature Engineering**: Creation of engagement and age-based cohorts.
3. **Statistical Distribution**: Analysis of usage intensity and outlier treatment using **Winsorization**.
4. **Bivariate & Multivariate Analysis**: Intersection of demographics, plan types, and consumption.
5. **Strategic Insights**: Final executive report with actionable business recommendations.

## How to Execute
To view and interact with the analysis:

1. **Option A: Google Colab (Recommended)**
   * Click on the `ConnectaTel_Customer_Behavior_Audit_2024.ipynb` file in this repository.
   * Copy the URL of the page.
   * Go to [Google Colab](https://colab.research.google.com/) -> GitHub Tab -> Paste the URL.

2. **Option B: Local Environment**
   * Clone the repository: `git clone https://github.com/ALEX-TORRES-B/ConnectaTel-Customer-Behavior-Audit.git`
   * Install dependencies: `pip install pandas seaborn matplotlib numpy`
   * Run Jupyter Notebook or VS Code.

## Reproduction Guide
1. Ensure the datasets (CSV files) are in the `/datasets/` folder or in the same root directory as the notebook.
2. Follow the chronological order of the cells to maintain data transformation logic.
3. Use the **Table of Contents** within the notebook to navigate between the Audit and the Strategic Insights sections.
