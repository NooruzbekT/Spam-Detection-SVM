# Spam Email Detection

## Description
This project is focused on detecting spam emails using machine learning techniques. The dataset used for training is `enron_spam_data.csv`, which contains labeled email messages classified as spam or non-spam. The model is built using `LinearSVC` from Scikit-Learn.

## Dataset
The dataset is stored in `enron_spam_data.csv` and should be placed in the appropriate directory before training the model.

## Project Structure
- `spamemail.ipynb` — Jupyter Notebook with data preprocessing, model training, and evaluation.
- `data/` — Directory for storing datasets.
- `models/` — Directory for saving trained models.

## Installation and Setup
### 1. Clone the Repository
```sh
git clone <repository-url>
cd Spam-Detection-SVM
```
### 2. Install Dependencies
It is recommended to use a virtual environment:
```sh
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate  # For Windows
pip install -r requirements.txt
```
### 3. Download or Prepare the Dataset
Ensure `enron_spam_data.csv` is present in the `data/` directory.

### 4. Run Jupyter Notebook
```sh
jupyter notebook
```
Open `spamemail.ipynb` and execute the cells sequentially.

## Model Training Steps
1. Load the dataset from CSV.
2. Preprocess text (tokenization, vectorization, and cleaning).
3. Train the `LinearSVC` model.
4. Evaluate model performance.
5. Save the trained model for future use.

## Contact
For questions or suggestions, feel free to create an issue in the repository.

## License
This project is distributed under the MIT License.
