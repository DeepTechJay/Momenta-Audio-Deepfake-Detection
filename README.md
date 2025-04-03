# Momenta-Audio-Deepfake-Detection

# Momenta Audio Deepfake Detection

## Overview
This project aims to detect audio deepfakes using machine learning techniques. It processes audio data, extracts features, and classifies real vs. fake audio recordings.

## Dataset
We use the **ASVspoof 2021** dataset, which contains both real and fake audio samples. The dataset is structured as follows:
- `Train`: Training set with labeled real and fake audio samples
- `Validation`: Validation set for hyperparameter tuning
- `Test`: Testing set for final evaluation

## Installation
1. Clone this repository:
   ```bash
   git clone git@github.com:DeepTechJay/Momenta-Audio-Deepfake-Detection.git
   cd Momenta-Audio-Deepfake-Detection
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

## Usage
1. Ensure the dataset is downloaded and extracted into the correct directory.
2. Run the Jupyter Notebook for model training and evaluation:
   ```bash
   jupyter notebook Momenta_Audio_Deepfake_Detection.ipynb
   ```
3. Modify parameters and re-run cells as needed.

## Model Details
- **Feature Extraction**: MFCC, Spectrograms
- **Classifier**: CNN / LSTM / SVM
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score

## Results
The model achieves an accuracy of **X%** on the validation set. Further improvements can be made by tuning hyperparameters and increasing dataset diversity.

## Contributing
Feel free to fork the repo, make improvements, and submit a pull request.

## License
This project is licensed under the MIT License.

## Contact
For any questions, contact jadjaydeep007@gmail.com

.
