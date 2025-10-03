# Reproducing results:
Results in the report was provided by the code in cnn_coil100.ipynb. 
## Environment:
### Python version `3.12.4`
### Necessary packages:
```
tensorflow==2.18.0
numpy==2.0.2
matplotlib==3.10.0
scikit-learn==1.4.2
keras==3.5.0
``` 
## Steps to run:
1. Add packages in a `requirements.txt` file.
2. Create a python virtual environment with the following command line:
``python -m venv venv``
3. Activate the  virtual environment with the following command: 
``venv\Scripts\activate``
4. Install required packages with the following command:
``python -m pip install -r requirements.txt`` 
5. Extract COIL-100 dataset in `./%PROJECT_DIRECTORY%/dataset/` folder
6. Run the project in the notebook (`cnn_coil100.ipynb`).