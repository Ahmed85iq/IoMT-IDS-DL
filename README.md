# IoMT-IDS-DL
 IoMT-IDS: Deep Learning-Based Intrusion Detection System

📌 Overview
This project presents an Intrusion Detection System (IDS) for Internet of Medical Things (IoMT) to enhance security and detection efficiency.
 The model integrates advanced feature selection techniques and deep learning for improved anomaly detection.

🔹 Key Features:

Feature Selection: Utilizes Information Gain (IG) & Recursive Feature Elimination (RFE) to select the most relevant 50% of features.

Dimensionality Reduction: Implements a Deep Autoencoder (DAE) for feature compression.

Classification Model: Uses a Deep Neural Network (DNN) for intrusion detection.

Datasets: Trained and evaluated on CICIDS2017 and WUSTL-EHMS-2020.

High Performance:

CICIDS2017: 99.61% accuracy

WUSTL-EHMS-2020: 99.93% accuracy with reduced training time.

Dependencies
Python 3.10
TensorFlow / PyTorch
Scikit-learn
Pandas & NumPy
Matplotlib & Seaborn

Acknowledgments

Special thanks to the creators of CICIDS2017 and WUSTL-EHMS-2020 datasets for their contribution to cybersecurity research.
