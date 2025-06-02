# Data Mining for Drug-Condition Causal Associations

## Project Overview

This project explores a data mining-based approach to systematically investigate and determine causal associations between pharmaceutical drugs and medical conditions. The primary goal is to leverage real-world healthcare data to identify potential adverse drug reactions, evaluate drug efficacy, and ultimately contribute to improved patient safety and treatment outcomes.

The study addresses the significant challenges of establishing causal links from observational healthcare data, including confounding factors, biases, and the inherent complexity of drug-condition interactions.

## Key Features & Contributions

* **Extensive Data Preprocessing:** Developed robust methods to integrate and clean heterogeneous large-scale electronic health records (EHRs), adverse event reporting databases, and drug information sources (specifically from drugs.com). This included handling missing values, standardizing textual data (e.g., side effects), and performing feature engineering to derive informative features.
* **Exploratory Data Analysis (EDA):** Conducted comprehensive exploratory data analysis to understand the prevalence of medical conditions, the distribution of drug ratings, and the relationships between drug activity, user ratings, and reported side effects. Identified and analyzed the top 10 most commonly reported side effects after thorough text normalization.
* **Predictive Model Development:** Implemented and evaluated predictive machine learning models in Python to forecast user ratings for drugs. This included:
    * **Linear Regression Model:** Built to predict user ratings based on features like drug activity and encoded categorical variables, assessing its performance with RMSE and R-squared.
    * **Decision Tree Regression Model:** Employed to forecast user ratings using the number of side effects, drug effectiveness (activity percentage), and Controlled Substances Act (CSA) classification.
* **Impact & Insights:** The findings from this project contribute to a better understanding of drug-condition relationships, can aid in detecting potential Adverse Drug Reactions (ADRs), support pharmacovigilance, and inform personalized medicine strategies.

## Technologies Used

* **Python**
    * `pandas` (for data manipulation and analysis)
    * `numpy` (for numerical operations)
    * `scikit-learn` (for machine learning models: Linear Regression, Decision Tree Regression)
    * `matplotlib` (for data visualization)
    * `seaborn` (for enhanced data visualization)
    * `re` (for regular expressions in text processing)
    * `itertools` (for flattening lists)

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Soumya98-dev/Drug-Condition-Causal-Associations.git](https://github.com/Soumya98-dev/Drug-Condition-Causal-Associations.git)
    cd Drug-Condition-Causal-Associations
    ```
2.  **Install the required packages:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```

## Usage
1.  **Start Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
2.  **Open the relevant notebook:** Navigate to and open `Intelligent-Systems-Final-Project.ipynb` (or similar, depending on your file structure) to view the code, analysis steps, and results.

## Contributing

Feel free to fork the repository, make improvements, and submit pull requests.

## License

License: MIT
