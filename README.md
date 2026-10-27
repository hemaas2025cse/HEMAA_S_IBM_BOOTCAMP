# ML Network Intrusion Detector

**Submitted by:** HEMAA S

## Project description
A beginner-friendly machine-learning prototype that classifies labeled network-flow records as benign or potentially malicious using a Random Forest classifier.

> Educational prototype only. It is not a production security system.

## Dataset
Use the official [CIC-IDS2017 dataset page](https://www.unb.ca/cic/datasets/ids-2017.html). Download a labeled CSV file and place it in this folder as `network_traffic.csv`.

## Technologies used
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Files
- `HEMAA_S_ML_Network_Intrusion_Detector.ipynb` — complete notebook
- `requirements.txt` — Python dependencies
- `HEMAA_S_ProjectReport.docx` — project report
- `README.md` — project overview and instructions

## Setup and run
1. Install Python 3.10 or newer.
2. Open a terminal in this folder.
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Download a labeled CSV from the official dataset page and save it as `network_traffic.csv` in this folder.
5. Launch Jupyter:

   ```bash
   jupyter notebook
   ```

6. Open `HEMAA_S_ML_Network_Intrusion_Detector.ipynb` and run cells from top to bottom.

## Expected output
The notebook prints model accuracy and a classification report, and displays a confusion matrix and label-distribution chart. Results depend on the selected dataset and should be filled into the report only after running the notebook.

## Important notes
- The notebook expects a target column named `Label`, `Class`, or `Target`.
- Use a manageable dataset subset if memory is limited.
- Do not treat predictions as definitive security findings.
