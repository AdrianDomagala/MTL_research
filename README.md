# MTL_research
## Repository trying to reproduce research *Exploring Multi-Task Learning for Explainability* by Foivos Charalampakos and Iordanis Koutsopoulos for Adult dataset https://archive.ics.uci.edu/dataset/2/adult
## Main parts of code:
- *Dataset Preprocessing* - trying to prepare the dataset in a way similar to one in the research
- *Comparison of MLP and Linear Model* - training and evaluation of Multi-Layer Perceptron and Logistic Regression models on the dataset
- *Comparison of STL and MTL approaches* - The Single Task Learning approach trains a surrogate model on already trained MLP in opposite to the Multi-Task Learning approach where both models are trained simultaneously.
- *Testing Models* - testing how different values of alpha parameter influence model accuracy and fidelity also testing Logistic Regression and Linear Regression as a surrogate model.
