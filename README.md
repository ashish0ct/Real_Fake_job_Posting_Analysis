# Real Fake Job Posting Analysis

A data science project that analyzes and classifies real versus fake job postings using machine learning techniques.

## Project Overview

This project uses Python and various data science libraries to analyze job postings and determine whether they are legitimate or fraudulent. The analysis helps identify patterns and characteristics that distinguish real job postings from fake ones.

## Technologies Used

- Python 3.x
- Jupyter Notebook
- Key Libraries:
  - pandas: For data manipulation and analysis
  - scikit-learn: For machine learning models
  - matplotlib/seaborn: For data visualization
  - numpy: For numerical operations

## Project Structure

```
├── .idea                     # IDE configuration files
├── ipynb_checkpoints         # Jupyter notebook checkpoints
├── fake_job_postings.csv     # Dataset containing job postings
├── main2.ipynb              # Main Jupyter notebook with analysis
└── README.md                # Project documentation
```

## Dataset

The project uses a dataset (`fake_job_postings.csv`) that contains various features of job postings, including:
- Job title and description
- Company information
- Location details
- Required qualifications
- Salary information
- Posting requirements
- Label indicating whether the posting is fraudulent or legitimate

## Analysis Components

The Jupyter notebook (`main2.ipynb`) contains several key analysis components:

1. Data Loading and Preprocessing
   - Loading the CSV file
   - Handling missing values
   - Feature engineering
   - Text preprocessing

2. Exploratory Data Analysis (EDA)
   - Distribution of real vs fake jobs
   - Analysis of job posting characteristics
   - Correlation analysis
   - Feature importance

3. Machine Learning Models
   - Text vectorization
   - Model training and evaluation
   - Performance metrics
   - Prediction results

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/ashish0ct/Real_Fake_job_Posting_Analysis.git
cd Real_Fake_job_Posting_Analysis
```

2. Install required dependencies:
```bash
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `main2.ipynb` to view the analysis

## Results

The project demonstrates the application of machine learning techniques to identify fraudulent job postings, helping:
- Protect job seekers from scams
- Understand patterns in fake job postings
- Develop automated detection systems

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
