
# Project Title

This project follows the CRISP-DM process for data mining and analytics.

## Directory Structure

- **01_business_understanding:** Contains documents on objectives, requirements, and stakeholder interviews.
- **02_data_understanding:** Houses raw data, exploratory analyses, and initial findings.
- **03_data_preparation:** Includes scripts and notebooks for data cleaning, transformation, and feature engineering.
- **04_modeling:** Holds scripts and notebooks for model training and experimentation.
- **05_evaluation:** Contains model evaluation metrics, plots, and performance reports.
- **06_deployment:** Provides deployment scripts and monitoring documentation.

## Python Virtual Environment Setup

This project uses a Python virtual environment to manage dependencies. The virtual environment is created in a directory called `.venv` using Python 3.11.

### How to Activate the Virtual Environment

**On Ubuntu (or other Linux distributions):**

1. Navigate to the project root directory:
   ```
   cd project-root
   ```
2. Activate the virtual environment:
   ```
   source .venv/bin/activate
   ```
   Your prompt should change to indicate the virtual environment (usually showing `.venv`).

3. Install required packages (if added to requirements.txt):
   ```
   pip install -r requirements.txt
   ```
4. When finished, deactivate the environment by typing:
   ```
   deactivate
   ```

**On Windows:**

1. Navigate to the project root directory:
   ```
   cd project-root
   ```
2. Activate the virtual environment:
   - For PowerShell:
     ```
     .\.venv\Scripts\Activate.ps1
     ```
   - For Command Prompt:
     ```
     .\.venv\Scripts\activate
     ```
3. Install required packages (if updated in requirements.txt):
   ```
   pip install -r requirements.txt
   ```
4. Deactivate the environment by running:
   ```
   deactivate
   ```

