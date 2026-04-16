# Hotel Booking Cancellation Risk Prediction | Graduate ML Project

## Project Overview

This project applies machine learning to predict hotel booking cancellation risk for ABC Hotels. The business objective is to identify bookings with high cancellation risk (expressed as a probability between 0 and 1), enabling hotel management to implement targeted retention strategies such as additional advertisements and promotional offers.

**Customer:** ABC Hotels  
**Dataset:** 35,000+ historical hotel bookings with cancellation outcomes

---

## Project Structure

```
machine-learning/
├── code/                                # Jupyter notebooks for analysis
│   ├── 02 preliminary results/          # Initial findings and EDA
│   └── 03 final report and appendices/  # Final model iterations and deliverables
├── data/                                # Project datasets
│   ├── project_data.csv                 # Main dataset
│   ├── project_data.xlsx                # Excel format
│   ├── project_data_test.xlsx           # Test set
│   └── DataDictionaryAttempt.xlsx       # Feature definitions
├── reports/                             # Formal report deliverables
│   ├── 01 analytic plan/
│   ├── 02 preliminary results/
│   └── 03 final report and appendices/
├── instructions and feedback/           # Project requirements and feedback
└── testing and output/                  # Additional outputs and experiments
```

---

## Dataset

**Format:** CSV and XLSX  
**Sample Size:** 35,000+ bookings  
**Target Variable:** Booking cancellation (binary)  
**Features:** Hotel attributes, booking characteristics, and customer behavior patterns  

Refer to `DataDictionaryAttempt.xlsx` for complete feature documentation.

---

## Project Phases

This project follows a structured machine learning lifecycle:

### 1. Analytic Plan
- Define business objectives and success metrics
- Outline data preparation strategy
- Specify feature engineering approach
- Document machine learning methodology

### 2. Preliminary Results
- Exploratory data analysis (EDA)
- Data preparation and feature engineering
- Initial model development and evaluation
- Client feedback incorporation

### 3. Final Report
- Comprehensive analysis with refined models
- Comparison of three multiple dense neural network architectures
- Evaluation using ROC curves, AUC, and calibration plots
- Model selection and business recommendations
- Ready for client presentation

---

## Key Deliverables

**Notebooks:**
- `DSE6211_PreliminaryReport_PythonNotebook.ipynb` – Preliminary findings and exploratory analysis
- `FinalProject_Take1.ipynb` – Neural Network Model 1
- `FinalProject_Take2.ipynb` – Neural Network Model 2
- `FinalProject_Take3.ipynb` – Neural Network Model 3

**Report Specifications:**
- Executive Summary (1-2 pages)
- Approach & Data section
- Detailed Findings and Evaluation
- Recommendations for deployment
- Appendix with supporting analysis
- Maximum 20 single-spaced pages (excluding appendices)

---

## Reports and Documents

### Project Phase Reports (PDF)
- [Analytic Plan](reports/01%20analytic%20plan/DSE6211_%20AnalyticPlan_JMLemieux.pdf) – Initial project strategy and approach
- [Preliminary Results](reports/02%20preliminary%20results/DSE6211_PreliminaryResults_JMLemieux.pdf) – Initial findings and feedback

### Final Report (PDF)
- [Final Report](reports/03%20final%20report%20and%20appendices/DSE6211_FinalReport_JMLemieux.pdf) – Comprehensive final deliverable identifying the recommended model

### Neural Network Model Details (PDF)
- [Neural Network Model 1](reports/03%20final%20report%20and%20appendices/FinalProject_Take1.pdf)
- [Neural Network Model 2](reports/03%20final%20report%20and%20appendices/FinalProject_Take2.pdf)
- [Neural Network Model 3](reports/03%20final%20report%20and%20appendices/FinalProject_Take3.pdf)

### Additional Notes
- [Model Comparison Notes](testing%20and%20output/Final%20Project%20differences%20between%20models.docx) – Neural network model comparison notes

---

## Model Requirements

✓ Compare at least two dense neural network models  
✓ Use ROC curves for model comparison  
✓ Report AUC scores  
✓ Include calibration plots  
✓ Select final model with business justification  
✓ Define implementation strategy for production use

---

## Running the Notebooks

### Environment Requirements
- **Python Version:** 3.12.8
- **Required Packages:** pandas, numpy, scikit-learn, torch, seaborn, matplotlib

### Installation

Before running the notebooks, ensure all required packages are installed:

```python
%pip install pandas numpy scikit-learn torch seaborn matplotlib
```

Alternatively, from the terminal:

```bash
pip install pandas numpy scikit-learn torch seaborn matplotlib
```

### Executing Notebooks

1. Open the desired notebook in Jupyter or VS Code
2. Install dependencies (if not already done)
3. Run cells sequentially from top to bottom
4. Outputs will be generated in-place with visualizations and model results

**Notebook Execution Order:**
1. `DSE6211_PreliminaryReport_PythonNotebook.ipynb` – Data exploration and preliminary analysis
2. `FinalProject_Take1.ipynb` – Neural Network Model 1
3. `FinalProject_Take2.ipynb` – Neural Network Model 2
4. `FinalProject_Take3.ipynb` – Neural Network Model 3
