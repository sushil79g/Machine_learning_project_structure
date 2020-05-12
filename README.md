# Machine learning project structure

## Project structure contains:
### 1) api</br> 
Consists of scripts which serialize the API calls and act as a endpoint faciliating for project functions.
### 2) data</br>
Data in different format. it is further divided into raw directory where raw data is stored and preprocessed directory where pre-processed raw data are stored.
### 3) evaluation</br>
Consists of script which evaluate the model performance using different metrics. 
### 4) examples</br>
It consists of doc and example showing how we can use the project, different functions etc.  
### 5) notebooks</br>
All the ipython notebooks used for EDA, visualization and verification of concept (POC).
### 6) project</br>
Here consists of all the project files from dataset downloading script or accesing dataset from data folder, model building, Neural network schema, folder to save weights, and different utils functions.
### 7) project_cli</br>
Scripts which faciliates Command line interface for  taining, testing and other features. 
### 8) tasks</br>
Contains batch script which can be used for downloading files from web or batch to auto test, lint project.
### 9) training</br>
Contains all experiments preperation, way on auto running experiments and updating metadata.
### 10) Dockerfile</br>
This helps in dockerizing whole system.
### 11) requirements.txt</br>
requirements files contains all the module used while building the project.
