# EDA of Alert Data

This project provides a comprehensive exploratory data analysis (EDA) pipeline for alert data, including data loading, cleaning, feature engineering, pattern and performance analysis, and automated profiling. The notebook is designed for robust, memory-efficient analysis and outputs both HTML and JSON reports.

## Features
- Data loading and cleaning functions
- Feature engineering for time-based and categorical features
- Pattern and performance analysis with visualizations
- Automated profiling using `ydata_profiling`
- Outputs summary reports in HTML and JSON formats

## Getting Started

### Prerequisites
- Python 3.7+
- Recommended: Jupyter Notebook or VS Code with Jupyter extension
- Required Python packages:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - ydata_profiling (for auto profiling)

### Installation
1. Clone this repository:
   ```sh
   git clone <your-repo-url>
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

### Usage
1. Open `eda-of-alert-data.ipynb` in Jupyter or VS Code.
2. Update the `DATA_PATH` variable if your data file is in a different location.
3. Run the notebook cells sequentially.
4. The pipeline will generate an HTML report and a JSON summary in the output directory.

## File Structure
- `eda-of-alert-data.ipynb` — Main notebook with the EDA pipeline
- `requirements.txt` — List of required Python packages
- `README.md` — Project overview and instructions
- (Optional) `auto_eda_report.html` — Generated EDA report
- (Optional) `eda_output.json` — Generated summary output

## Recommended .gitignore
A `.gitignore` file is included to avoid uploading unnecessary files to GitHub.

## License
Specify your license here (e.g., MIT, Apache 2.0, etc.)
