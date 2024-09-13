# MTL_research
This repository contains code that is part of a master's thesis titled "Multi-task learning in Self eXplainable Deep Neural Networks". 

Thesis analyzes and extends the research "Exploring Multi Task Learning for Explainability" by Foivos Charalampakos and Iordanis Koutsopoulos.The primary objective is to reproduce the results of the original study to evaluate the effects of employing a Multi-Task Learning approach on model performance across two tasks: prediction (measured by mean squared error and accuracy) and explainability (measured through Global Fidelity). Additionally, this thesis investigates the influence of the approach on local explainability. The outcomes are compared with those derived from a Single Task Learning approach, which serves as the reference baseline. Moreover, an extension is introduced through the incorporation of local surrogate models and neighborhood fidelity during training, with the aim of assessing their impact on various performance metrics of the models.

## Contents

- MT_Datasets_Overview.ipynb: This notebook provides an analysis and preprocessing of the datasets.
- MT_Preparatory_Code.ipynb: This file contains all the essential definitions, including models, classes, and functions.
- MT_Training_and_Testing.ipynb: This notebook executes the training and testing of the models and conducts experiments.

## Requirements 

The requirements are described in the environment.yaml file. Code can be run using a virtual environment created with Anaconda. Sample commands: 
```
    conda env create -f environment.yaml
    conda activate MTL_env
    conda jupyter lab 
```