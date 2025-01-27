# Zeotap-Assignment
### README.md for Zeotap Data Science Intern Assignment

```markdown
# Zeotap Data Science Intern Assignment

This repository contains the solution for the Data Science Intern assignment provided by Zeotap. The assignment covers three key tasks: 
1. Exploratory Data Analysis (EDA) and business insights generation.
2. Development of a Lookalike Model for customer recommendations.
3. Customer Segmentation using clustering techniques.

## Repository Structure

```plaintext
├── Shreya_Kabra_EDA.ipynb            # Jupyter Notebook for EDA and business insights
├── Shreya_Kabra_Lookalike.ipynb      # Jupyter Notebook for Lookalike Model
├── Shreya_Kabra_Clustering.ipynb     # Jupyter Notebook for Customer Segmentation
├── Customers.csv              # Provided customer data
├── Products.csv               # Provided product data
├── Transactions.csv           # Provided transaction data
├── Shreya_Kabra_Lookalike.csv  # Output of the Lookalike Model
├── Shreya_Kabra_Clustering.csv # Clustering results
├── Shreya_Kabra_EDA.pdf        # PDF report with business insights
└── README.md                  # Repository documentation
```

## Task Descriptions

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- Conducted EDA on the provided datasets (`Customers.csv`, `Products.csv`, and `Transactions.csv`).
- Identified and visualized key patterns in customer behavior and product trends.
- Derived five actionable business insights for strategic decision-making.
- **Deliverables**:
  - **Notebook**: `Shreya_Kabra_EDA.ipynb`
  - **Report**: `Shreya_Kabra_EDA.pdf`

### Task 2: Lookalike Model
- Developed a Lookalike Model to recommend similar customers based on profile and transaction history.
- Utilized cosine similarity for customer recommendations and assigned similarity scores.
- Provided top 3 recommendations for the first 20 customers.
- **Deliverables**:
  - **Notebook**: `Shreya_Kabra_Lookalike.ipynb`
  - **Results**: `Shreya_Kabra_Lookalike.csv`

### Task 3: Customer Segmentation
- Performed customer segmentation using K-Means clustering.
- Evaluated clustering quality using the Davies-Bouldin Index and visualized clusters.
- Identified optimal clusters for effective customer profiling.
- **Deliverables**:
  - **Notebook**: `Shreya_Kabra_Clustering.ipynb`
  - **Results**: `Shreya_Kabra_Clustering.csv`

## Key Insights and Results
- **EDA**: Analyzed customer behaviors, product trends, and transaction statistics to provide meaningful insights.
- **Lookalike Model**: Achieved accurate customer recommendations with cosine similarity.
- **Clustering**: Determined optimal customer segments with low Davies-Bouldin Index, aiding targeted marketing strategies.

## Requirements
- **Python Version**: 3.8+
- **Libraries Used**:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/zeotap-ds-assignment.git
   ```
2. Open the Jupyter Notebooks (`.ipynb`) in a Python environment or Google Colab.
3. Follow the notebooks step-by-step to reproduce results.

## Submission
- **Deadline**: 27 January 2025
- Public GitHub Repository Link: [Insert your repository link here]
