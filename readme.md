# Google Play Store Data Analysis

This project performs a detailed Exploratory Data Analysis (EDA) and feature engineering on the Google Play Store dataset. The main goal is to derive insights from app data and prepare the dataset for potential future use in predictive modeling, focusing exclusively on EDA and feature transformation steps.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [License](#license)
- [Contributing](#contributing)

## Overview

The project explores the Google Play Store data to understand trends and patterns that can inform better app development and marketing strategies. By thoroughly analyzing features such as app ratings, installations, and categories, and enhancing the dataset through feature engineering, the project sets a foundation for any subsequent data-driven tasks.

## Features

- **Exploratory Data Analysis (EDA)**: Utilizes visual and statistical methods to explore app data from the Google Play Store, identifying trends and patterns.
- **Feature Engineering**: Processes raw data to create new features that could better expose the underlying patterns to predictive algorithms, although this project stops at the feature engineering phase.

## Installation

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/google-play-store-analysis.git
   cd google-play-store-analysis
```
2. **Create a Python virtual environment:**
```bash
python -m venv env
source env/bin/activate  # Use `env\Scripts\activate` on Windows
```
3. **Install the required dependencies:**

```bash
pip install -r requirements.txt
```
 ## Usage
To view and run the analysis:
 
 ```bash
jupyter notebook notebook.ipynb
```
Follow the steps outlined in the notebook to see the analysis and data transformations.

## Project Structure

-`notebook.ipynb`: Jupyter notebook with all the EDA and feature engineering code.
-`googleplaystore.csv`: Original dataset file.
-`googleplaystore_cleaned.csv`: Cleaned and transformed dataset after initial preprocessing.
-`requirements.txt`: Lists all the necessary Python packages for the project.

## Dependencies
-`pandas`
-`numpy`
-`matplotlib`
-`seaborn`
-`scipy`
These are detailed in the requirements.txt file to facilitate easy setup.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contributing
We encourage contributions to improve the analysis or extend the feature engineering. Please open an issue or submit a pull request with your changes or suggestions.