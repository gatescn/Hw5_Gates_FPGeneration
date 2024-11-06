The purpose of this repository:
- Source code for python learning model training project on Lipophilicity dataset with the purpose of Finger Print Generation.
------
Model: MLPRegressor (sklearn.neural_network)
------
Training data: Lipophilicity dataset

Lipophilicity is a dataset curated from ChEMBL database containing experimental results on octanol/water distribution coefficient (logD at pH=7.4). Due to the importance of lipophilicity in membrane permeability and solubility, the task is of high importance to drug development.

The data file contains a csv table, in which columns below are used:
     "smiles" - SMILES representation of the molecular structure
     "exp" - Measured octanol/water distribution coefficient (logD) of the compound, used as label

Reference:
Hersey, A. ChEMBL Deposited Data Set - AZ dataset; 2015. https://doi.org/10.6019/chembl3301361

INSTALLATION PROCESS:
Step 1: clone this repository
Step 3: download visual studio code
Step 4: Download Anaconda Navigator & perform the installation process
    - https://www.anaconda.com/products/navigator
Step 5: Open Anaconda Navigator and select 'Environment' then select 'import'. Once import window appears navigate to the environment.yml
file and select this file. (this will create the anaconda env for this project). (You can rename the environment to whatever just remember the name)
Step 6: Navigate to the script folder and select the Hw5_Gates script and open in Visual Studio Code.
Step 7: Visual studio will prompt you to select your python kernal, Click 'python environments' and select the name of the environment you made with the environment.yml file.
Step 8: select run all (the initial imports will take a few minutes at first)

USE:
to update the following hyper parames for the MPRegressor model:
- hidden layer size
- max iteration

update the values in the config.json