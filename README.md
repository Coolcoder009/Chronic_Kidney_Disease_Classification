# Chronic Kidney Disease Classifier
Chronic Kidney Disease Classification is a project meant to predict the Kidney disease affected.

## Dataset and Model
This is the link to my dataset and the model saved:
https://drive.google.com/drive/folders/1u0cFrIKXKTt_fPcj2FTTgb69_5KroYvH

## Installation
1. Clone the repository 
```bash 
git clone <repository-url>
cd <repository-directory>
```

2. To install the required dependencies, run the following command:
```bash
pip install -r requirements.txt
```

3. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
```

## How It Works
### Algorithms Used
The project leverages the ResNet 101 deep learning algorithm to classify Chronic Kidney Disease from medical images.

<ul>
<li><strong>ResNet 101:</strong> A deep residual network with 101 layers.</li>
</ul>

### Model Training
The model is trained on a dataset of kidney images. The training process involves the following steps:

<ul>
<li><strong>Data Preprocessing:</strong> Images are preprocessed to ensure uniformity and suitability for model input.</li>
<li><strong>Model Training:</strong> The model is trained using the preprocessed data.</li>
<li><strong>Validation:</strong> Model performance is validated using a separate validation dataset.</li>
<li><strong>Testing:</strong> The trained model is tested on a test dataset to evaluate its accuracy and performance.</li>
</ul>

### Example Usage
To run the model and train it on the dataset, follow these steps:

### Open Jupyter Notebook:
Open the notebook file (.ipynb) and execute the cells to train and evaluate the model. The notebook includes:

<ul>
<li>`CTKidney.ipynb`</li>
</ul>

### Results
The results of the model training and evaluation are presented in the notebook. You can find metrics such as accuracy, precision, recall, and confusion matrices for the model.

### File Handling
The project handles medical image files in various formats. The images are loaded, preprocessed, and then fed into the model for training and evaluation.
