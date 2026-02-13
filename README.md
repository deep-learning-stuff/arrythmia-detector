# HeartbeatVision: ECG Arrhythmia Classification 🫀

HeartbeatVision is a Deep Learning project focused on the automated detection of cardiac anomalies through Electrocardiogram (ECG) signals. The model classifies heartbeats into two primary categories: healthy individuals and patients with arrhythmias or other cardiac pathologies.

## 🚀 Project Overview
Manual interpretation of ECGs requires expert knowledge and significant time. This project aims to automate the initial screening process using Neural Networks, enabling rapid identification of pathological patterns that may indicate critical health conditions.

### Key Features:
* **Signal Processing:** Data cleaning, normalization, and balancing of ECG signals for robust analysis.
* **Deep Learning Architecture:** Built with **PyTorch**, utilizing a Multi-Layer Perceptron (MLP) with optimized activation functions for binary classification.
* **Performance Evaluation:** Includes tracking of Accuracy and Loss metrics to ensure diagnostic reliability.
* **Variational Analysis:** Includes a dedicated notebook for hyperparameter testing and model optimization.

## 🛠️ Technologies Used
* **Language:** Python
* **AI Framework:** PyTorch
* **Data Analysis:** NumPy, Pandas
* **Visualization:** Matplotlib
* **Environment:** Google Colab / Jupyter Notebook

## 📈 Methodology
The model is trained using a dataset of pre-segmented heartbeat signals. The workflow follows these steps:
1.  **Data Loading:** Integration with Google Drive for handling large datasets.
2.  **Architecture Design:** A neural network specifically tuned to extract temporal features from the heart's electrical activity.
3.  **Optimization:** Implementation of the `Adam` optimizer and `BCELoss` (Binary Cross Entropy) for precise weight adjustments.

## 💻 Setup & Usage
The project is organized into Jupyter Notebooks for a step-by-step execution:

1.  **Prerequisites:** Install the required dependencies:
    ```bash
    pip install torch pandas numpy matplotlib tqdm
    ```
2.  **Execution:**
    * Open `heartbeatvision.ipynb` in Google Colab or your local Jupyter environment.
    * Mount your Drive if the dataset is stored there.
    * Run the training cells to generate the model.
    * Use `heartbeatvision variaciones.ipynb` to explore different model architectures and variations.

## 👥 Authors
Developed as part of a Research Project (TR) on the application of Artificial Intelligence in the healthcare sector.

---
*Disclaimer: This project is for academic purposes and should not be used as a substitute for professional medical diagnosis.*
