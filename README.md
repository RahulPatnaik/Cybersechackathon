# Cyber Classifier

This project contains a machine learning model designed for text classification tasks. The code is implemented in Python using the Hugging Face Transformers library, and the workflow is detailed in the `model.ipynb` notebook.

## Prerequisites

Before running the project, ensure you have the following installed:
- Python 3.8 or higher
- pip
- Jupyter Notebook or JupyterLab

## Installation

1. **Clone the Repository**:
   ```
   bash
   git clone https://github.com/your-username/CYBERSECHACKATHON
   cd project-name
   ```


2. **Create a Virtual Environment (recommended):**
    ```
    bash
    Copy code
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```


## Model Setup
The pre-trained model and tokenizer files might not be included in the repository due to size constraints. Follow these steps to set up the model:

Download the Model and Tokenizer:

If the model files (```cyber_classifier_model``` and ```cyber_classifier_tokenizer```) are hosted elsewhere, download them from the provided link (e.g., Google Drive, Hugging Face Hub, etc.).
Place Files in Correct Directories:

Place the ```cyber_classifier_model``` folder inside models/.
Place the ```cyber_classifier_tokenizer``` folder inside models/.
Ensure ```label_encoder.joblib``` is inside the models/ folder.