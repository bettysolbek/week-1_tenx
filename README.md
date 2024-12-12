# AI Mastery Week 1 - Task 1

## Overview
This repository contains the progress for **Task 1** of the 10 Academy Artificial Intelligence Mastery Week 1 Challenge. The focus of Task 1 is setting up the development environment and performing basic exploratory data analysis (EDA) on the given financial news dataset.

## Repository Structure
```
├── .vscode/
│   └── settings.json               # VS Code environment settings
├── .github/
│   └── workflows/
│       ├── unittests.yml           # CI/CD configuration
├── .gitignore                      # Files to exclude from version control
├── requirements.txt                # Python dependencies
├── README.md                       # This file
├── src/
│   ├── __init__.py                 # Python module initialization
├── notebooks/
│   ├── EDA.ipynb                   # Exploratory Data Analysis notebook
│   └── README.md                   # Notebook-specific instructions
├── tests/
│   ├── test_sample.py              # Placeholder for unit tests
├── scripts/
│   ├── data_preparation.py         # Placeholder script for data preparation
```

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd AI-Mastery-Week1
   ```

2. Create and activate a Python virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Task 1 Details

### Objectives
1. Set up the project environment using Git and organize the repository structure.
2. Perform exploratory data analysis (EDA) on the financial news dataset to gain insights into:
   - Headline lengths
   - Articles per publisher
   - Trends in publication dates

### Key Scripts and Files

- **`notebooks/EDA.ipynb`**: Contains the Python code for EDA, including descriptive statistics and visualizations.
- **`requirements.txt`**: Lists the Python libraries required to run the project.
- **`.gitignore`**: Specifies files and directories to be excluded from version control.

### Sample EDA Insights
1. **Headline Length**: Analyzed the distribution of headline lengths in the dataset.
2. **Publisher Activity**: Identified the most active publishers contributing to the dataset.
3. **Publication Trends**: Explored the frequency of news articles over time.

## How to Contribute
1. Create a new branch for your work:
   ```bash
   git checkout -b task-1
   ```

2. Commit your changes with descriptive messages:
   ```bash
   git add .
   git commit -m "Task 1: Setup environment and perform EDA"
   ```

3. Push your changes and create a pull request to the `main` branch:
   ```bash
   git push origin task-1
   ```

## References
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [GitHub CI/CD](https://docs.github.com/en/actions)
- [Python Virtual Environments](https://docs.python.org/3/library/venv.html)

## Authors
Facilitators: Mahlet, Kerod, Rediet, Elias, Rehmet, Emitinan
