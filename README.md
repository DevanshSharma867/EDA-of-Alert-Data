# EDA of Alert Data

## Project Purpose
This project provides a robust, modular pipeline for performing exploratory data analysis (EDA) on alert or incident datasets. It is designed for flexibility, reproducibility, and easy adaptation to new datasets or business requirements.

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/DevanshSharma867/EDA-of-Alert-Data.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## How to Run the Notebook
1. Place your alert data CSV file in the `data/` directory, or use the provided `sample_alert_data.csv` for testing.
2. Open `eda-of-alert-data.ipynb` in Jupyter or VS Code.
3. Adjust the `DATA_PATH` and `OUTPUT_DIR` variables at the top of the notebook if needed.
4. Run all cells sequentially.
5. Outputs (HTML report, JSON summary) will be saved in the `output/` directory.

## Example Usage/Output
- Input: CSV file with alert data (see `data/sample_alert_data.csv` for format)
- Output: `output/auto_eda_report.html`, `output/eda_output.json`

## Credits/References
- [pandas documentation](https://pandas.pydata.org/)
- [ydata-profiling](https://github.com/ydataai/ydata-profiling)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)

