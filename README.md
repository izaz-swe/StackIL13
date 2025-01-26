# StackIL13: An Ensemble learning model for predicting Interleukin 13 Inducing Peptides Prediction

Interleukin-13 (IL-13) plays a vital role in immune regulation, particularly in allergic and inflammatory disorders like asthma and atopic dermatitis. This repository introduces StackIL13, a stacking ensemble model developed for accurate prediction of IL-13-inducing peptides.

# Key features of this research include:

<span style="font-weight: bold">Dataset: </span>Positive and negative datasets derived from IL13Pred. Website Link: https://webs.iiitd.edu.in/raghava/il13pred/dataset.php </br>
Feature Extraction: Leveraging the ILearnPlus tool for diverse peptide feature sets (e.g., CKSAAP, DPC, CTDC, and CTraid). </br>
Data Balancing: Adasyn algorithm used to address dataset imbalance. </br>
Feature Selection: Recursive Shapley Value applied to optimize model inputs. </br>
Model Performance: StackIL13 outperformed independent models in accuracy, AUC, and MCC, showcasing the effectiveness of ensemble learning in handling biological data. </br>
This repository includes the code and dataset necessary for reproducing results and advancing research in IL-13 prediction and immunological studies. By facilitating accurate predictions of IL-13-inducing peptides, StackIL13 paves the way for personalized treatments and enhanced understanding of IL-13’s role in disease progression.

# Methodology
The methodology involves feature extraction from a peptide sequence dataset, addressing class imbalance with ADASYN and SMOTE techniques. A 10-fold cross-validation process optimizes model hyperparameters, while SHAP-based feature selection identifies key features to enhance prediction accuracy for IL-13-inducing peptides.

<img src="https://github.com/izaz-swe/StackIL13/blob/main/final_il13_methodology.png" width="500px" height="400px"/>

