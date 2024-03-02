## Segment Shopping Customer

## The Approach
1 - Perform some quick EDA(Exploratory Data Analysis)<br>
2 - Use KMEANS Clustering Algorithm to create our segments<br>
3 - Use summary statistics on the clusters<br>
4 - Visualise the informations<br>

## Project Structure
```
weather-analysis/
├── data/
│   ├── raw/                 # Raw data files
│   ├── processed/           # Processed data files
│   └── external/            # External datasets or data obtained from external sources
├── notebooks/               # Jupyter notebooks for data exploration, and analysis
├── src/                     # Source code
│   ├── data_preprocessing/  # Scripts or modules for data preprocessing
│   ├── feature_engineering/ # Scripts or modules for feature engineering
│   ├── modeling/            # Scripts or modules for modeling (machine learning models)
│   └── evaluation/          # Scripts for model evaluation and performance metrics
├── reports/                 # Reports generated(HTML, PDF) from analysis and modeling
├── models/                  # Saved models or model artifacts
├── environment.yml          # Conda environment file specifying dependencies
├── README.md                # README file describing the project and its components
└── requirements.txt         # Python dependencies file (alternative to environment.yml)
```