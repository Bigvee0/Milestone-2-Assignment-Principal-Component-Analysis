# Anderson Cancer Center PCA Analysis for Donor Funding

## Project Overview
This project performs Principal Component Analysis (PCA) on the breast cancer dataset from `sklearn.datasets` to identify essential variables for securing donor funding at the Anderson Cancer Center. The analysis reduces the dataset to 2 principal components, implements logistic regression for prediction (bonus task), and provides insights for donor presentations to address the growing number of referrals.

## Files Included
- **Requirements.txt**: Lists dependencies required to run the scripts.
- **Demo_Quick_Analysis.py**: A lightweight script demonstrating PCA and logistic regression with basic visualizations and insights.
- **Anderson_Cancer_PCA.py**: A comprehensive script with detailed PCA analysis, visualizations, logistic regression, and insights for donor funding.
- **quick_pca_results.png**: Output visualization from `Demo_Quick_Analysis.py` (scatter plot and variance bar chart).
- **pca_analysis_results.png**: Output visualization from `Anderson_Cancer_PCA.py` (scatter plot, variance bar chart, feature loading heatmap, class separation plot).
- **logistic_regression_results.png**: Output visualization from `Anderson_Cancer_PCA.py` (ROC curve and confusion matrix).

## Setup Instructions
1. **Prerequisites**:
   - Python 3.12.3 or compatible version.
   - A command-line interface or Python IDE (e.g., Jupyter Notebook, VS Code).
   - Internet access for initial package installation.

2. **Install Dependencies**:
   - Create a virtual environment (optional but recommended):
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows: venv\Scripts\activate
     ```
   - Install required packages:
     ```bash
     pip install -r Requirements.txt
     ```

3. **Running the Scripts**:
   - To run the quick demo:
     ```bash
     python Demo_Quick_Analysis.py
     ```
     - Outputs: Console report, `quick_pca_results.png`.
   - To run the comprehensive analysis:
     ```bash
     python Anderson_Cancer_PCA.py
     ```
     - Outputs: Detailed console report, `pca_analysis_results.png`, `logistic_regression_results.png`.

## Outputs
- **Console Reports**:
  - `Demo_Quick_Analysis.py`: Dataset summary, PCA results, logistic regression metrics, and brief insights.
  - `Anderson_Cancer_PCA.py`: Dataset overview, feature statistics, PCA variance analysis, component loadings, logistic regression metrics, and detailed insights for donor funding.
- **Visualizations**:
  - `quick_pca_results.png`: PCA scatter plot and variance bar chart for top 10 components.
  - `pca_analysis_results.png`: Four-panel visualization (PCA scatter, variance bar chart, feature loading heatmap, class separation).
  - `logistic_regression_results.png`: ROC curve and confusion matrix for logistic regression.
- **Insights**: Both scripts provide insights for donor funding, with `Anderson_Cancer_PCA.py` offering a comprehensive report tailored to the growing referral challenge.

## Notes
- The scripts use the breast cancer dataset from `sklearn.datasets`, requiring no external data files.
- Ensure write permissions in the working directory for saving PNG files.
- For GitHub submission, clone the repository and follow the setup instructions above.
- To package as a ZIP:
  ```bash
  zip -r cancer_pca_analysis.zip Requirements.txt Demo_Quick_Analysis.py Anderson_Cancer_PCA.py
  ```

## Contact
For questions or issues, contact the data analyst team at Anderson Cancer Center.
