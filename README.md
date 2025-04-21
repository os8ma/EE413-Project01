# Spoken Digit Classification with FSDD

This project uses the [Free Spoken Digit Dataset (FSDD)](https://github.com/Jakobovski/free-spoken-digit-dataset) to classify spoken digits (0–9) using features extracted from time, frequency, and wavelet domains.

## 📁 Project Structure

- `ProjectVf.ipynb`: Main notebook for loading data, extracting features, and training models.
- `free-spoken-digit-dataset/`: Contains the audio recordings (WAV files).
- `requirements.txt`: Python dependencies.

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/fsdd-classification.git
   cd fsdd-classification

2. Install the required dependencies:
   pip install -r requirements.txt
3. Download the dataset (if not already included):
  git clone https://github.com/Jakobovski/free-spoken-digit-dataset
4.Run the notebook: Open ProjectVf.ipynb in Jupyter or VS Code and run all cells.

🧠 Features
Extracts features from:

Time domain (e.g., Zero-crossing rate)

Frequency domain (e.g., MFCCs, spectral features)

Wavelet domain

Uses Random Forest Classifier for classification

Includes data visualizations

🔍 References
Free Spoken Digit Dataset (FSDD)
