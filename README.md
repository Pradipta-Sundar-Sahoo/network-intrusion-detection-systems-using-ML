# Network Intrusion Detection System using Machine Learning

## Overview
This project aims to develop a Network Intrusion Detection System (NIDS) using machine learning techniques. The system analyzes network traffic data to detect various types of attacks, including but not limited to Fuzzers, Analysis, Backdoors, DoS, Exploits, Generic, Reconnaissance, Shellcode, and Worms. The UNSW-NB 15 dataset is used for training and testing the NIDS.

## Model Training and Evaluation
We trained multiple machine learning models and evaluated their performance using the following metrics: accuracy, precision, F1-score, and training time.

### Models Used
- Logistic Regression
- Decision Trees
- Extra Trees
- Random Forest
- Gradient Boosting
- Multilayer Perceptron (MLP)
- MLP with Keras
- GRU with Keras
- LSTM with Keras

### Evaluation Metrics
- Accuracy
- Precision
- F1-score
- Training Time

### Results
We built a dataframe summarizing the performance of each model:

![image](https://github.com/Pradipta-Sundar-Sahoo/network-intrusion-detection-systems-using-ML/assets/157369477/19a9d96c-cf6e-4fd9-b4a6-6993e72a4e46)


### Best Model
Based on the evaluation results, the Extra Trees model implemented achieved the highest accuracy, precision, and F1-score. It also had a reasonable training time, making it the best model for our Network Intrusion Detection System.

## Requirements
- Python 3.x
- Libraries: pandas, scikit-learn, numpy, keras, etc. (See `requirements.txt` for details)

## Usage
Clone the repository:
```sh
  git clone https://github.com/Pradipta-Sundar-Sahoo/network-intrusion-detection-systems-using-ML.git
````

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- Special thanks to the Australian Centre for Cyber Security (ACCS) for providing the UNSW-NB 15 dataset.
- Inspiration and guidance from related research papers and open-source projects.
