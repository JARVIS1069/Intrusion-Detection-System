# AI-Based Intrusion Detection System (IDS)

## Overview
This project implements an AI-Based Intrusion Detection System (IDS) using deep learning models to detect real-time cyber attacks. The system is designed to analyze network traffic and classify it as normal or malicious activity.

## Features
- Uses deep learning models for anomaly detection.
- Supports real-time attack detection.
- Trained on **CIC-IDS-2017** and **UNSW-NB15** datasets.
- Implements feature extraction and selection for improved model performance.
- Provides insights through visualizations and performance metrics.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: TensorFlow, Keras, Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
- **Tools**: Jupyter Notebook
- **Datasets**: CIC-IDS-2017, UNSW-NB15

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/AI-IDS.git
   cd AI-IDS
  

## Usage
1. Ensure the dataset files are placed in the appropriate directory.
2. Run the Jupyter Notebook:
   ```sh
   jupyter notebook IDS.ipynb
   ```
3. Follow the steps in the notebook to preprocess data, train models, and evaluate performance.
4. To test the trained model on new traffic data, run:
   ```sh
   python test_model.py --input data/sample_traffic.csv
   ```

## Project Structure
```
AI-IDS/
│── data/                  # Datasets and processed data
│── models/                # Trained models
│── notebooks/             # Jupyter notebooks
│── scripts/               # Python scripts for training and testing
│── requirements.txt       # Dependencies
│── README.md              # Project documentation
```

## Results
- The model achieved **high detection accuracy** on both CIC-IDS-2017 and UNSW-NB15 datasets.
- Evaluation metrics include **Precision, Recall, F1-Score, ROC Curve, and Confusion Matrix**.

## Future Improvements
- Implement real-time traffic monitoring.
- Enhance model robustness with adversarial training.
- Deploy the model as an API for easy integration.

## Contributions
Feel free to contribute by opening issues or submitting pull requests.

## License
This project is open-source and available under the MIT License.

## Contact
For any queries, reach out to [your email] or visit my GitHub profile: [your GitHub profile link].

