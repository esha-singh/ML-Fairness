----------------------------
    Files Description
----------------------------
- Describes files which can be executed like 'python <file-name>'
- Please use the 'requirements.txt' file with pip to install necessary dependencies. 'pip install -r requirements.txt'

ThresholdClassifier.py: 
    - Runs a threshold classifier on COMPAS dataset 
    - generates ROC, group-wise TPR, FPR and Prob graphs

adversarial_debiasing.py:
    - Runs a 2-layer neural network without de-biasing and with de-biasing on COMPAS data
    - Uses tensorflow-1.15
    - prints results before and after de-biasing
    - generates comparison graphs

reweighing_preproc.py:
    - Run re-weighing on logsitic regression model
    - Displays and generates comparison grpahs 

explore_credit.py:
    - Explores the credit dataset by running both Logistic Regression and SVC
    - Plots the graphs for FPR, TPR, Demographic parity to show the bias
    
 credit_reweighing_preproc.py:
    - Python file which runs re-weighing on logistic regrssion model for credit dataset
    - Plots the comparison graphs for various metrics
 
 credit_adversarial_debiasing.py:
    - Python file which runs 2-layer neural network without de-biasing and with de-biasing on credit dataset
    - Code uses Tensorflow
    - Plots the comparison graphs between before and after de-biasing

adult_explore.py:
    - Reads the pre-prcoessed data shared in data folder (adult.zip need to uncompress it)
    - Explores the adult dataset by running both Logistic Regression and SVC. 
    - Plots graphs for some features/attributes for visual analysis
    - Plots the graphs for FPR, TPR, Demographic parity to show the bias
    
adult_adversarial_debiasing.py:
    - Python file which runs 2-layer neural network without de-biasing and with de-biasing on Adult dataset
    - Code uses Tensorflow-1.5
    - prints results before and after de-biasing
    - generates comparison graphs
    
adult_reweighing_preproc.py:
    - Python file which runs re-weighing on logistic regrssion model for Adult dataset
    - Displays comparison graphs for various metrics (DP, EO, Disparate Impact)
