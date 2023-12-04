# Data and feature improved machine learning model for accurately predicting bond dissociation energies of diverse energetic materials
We developed a high-accuracy machine learning model for predicting the bond dissociation energy (BDE) of energetic materials (EMs), 
utilizing a reliable dataset of 778 synthesized compounds and a complementary feature representation. The model outperformed existing models, 
achieving an R2 of 0.98 and MAE of 8.8 kJ·mol-1 on an independent test set. Key highlights include the introduction of the PADRE paradigm for data augmentation 
and the utilization of an ensemble learning XGBoost architecture. This work provides a reliable prediction tool for EMs' BDE and offers methodological guidelines 
for machine learning in low-data regimes.


<img width="825" alt="image" src="https://github.com/cholin01/BDE-prediction-of-energetic-material/assets/152848794/3b5afdb9-b2af-46aa-8368-1fe023db11d0">


## breif introduction

In this work, we employed two types of descriptors, SEC descriptors obtained by running the "descriptors.py" file, and CBD descriptors as shown in "CBD.csv". <br>
If you wish to use our model for predicting the bond dissociation energy of energetic materials, please run the "predict.py" file.
