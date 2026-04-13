# Building Machine Learning Model in Python
## The repo shows step by step on how to build a machine learning model in Python

The dataset used in this model is training.csv as attached. 

The dataset is used for solubility of molecules, to determine whether a molecule is soluble in water or solvent and whether they are good for drug discovery for the candidates.

## DataSets Definitions
**1.   MolLogP (Molecular LogP)** It measures how well a compound dissolves in a non-polar solvent (fat/octanol) compared to          water. A high LogP indicates high lipophilicity (low solubility in water).

**2.   MolWt (Molecular Weight)** It is directly related to molecular size. Larger, heavier molecules often have different         solubilities and binding affinities than smaller ones.

**3.   NumRotatableBonds (Number of Rotatable Bonds)** Indicates the molecular flexibility or rigidity. A high number of              rotatable bonds suggests a more flexible, open-chain molecule, while a low number suggests a rigid structure.

**4.   AromaticProportion (Aromatic Proportion)** Indicates how much of the molecule is part of an aromatic ring structure,         which often makes it more rigid and affects polarity.

**5.   logS (Log of Solubility)** It is the target variable in solubility prediction models. A more negative value means the       molecule is less soluble in water.

The model involves relevant steps like data separation, data spliting into training set and testing set

Model buildig using both linear regression (lr) and random forest (rf)

Model Training in lr and rf

Model prediction in lr and rf

Model performance evaluation in lr and rf

Model Comparison in in lr and rf

Data visualization of prediction results

**NB: This project was built using [google colab jupyter notebook](https://colab.research.google.com/github/Zkyusya/ML_Model/blob/main/ML_Model.ipynb)**



