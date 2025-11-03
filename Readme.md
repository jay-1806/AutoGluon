# AutoGluon Assignment Part 1

A small collection of Colab notebooks where I train and explain AutoGluon models on Kaggle-style tabular data. Each notebook was run end to end in my Colab, and I recorded a short walkthrough video for each.

---

## Contents

Notebooks
1. autogluon_kaggle_ieee_fraud.ipynb  
   - Task: binary classification on IEEE fraud detection  
   - Output: submission_ieee_quick.csv  
   
2. autogluon_california_housing.ipynb  
   - Task: regression on California Housing Prices  
   - Output: submission_california.csv  
  
3. autogluon_tabular_quickstart.ipynb  
   - Task: quick demo of TabularPredictor fit → leaderboard → predict  

4. autogluon_tabular_multimodal.ipynb  
   - Task: multimodal tabular example (numerical + categorical + text if available) 

5. autogluon_tabular_feature_engineering.ipynb  
   - Task: automatic feature generation and its impact on scores  


Notes  
- I do not commit Kaggle datasets. Notebooks load data from Google Drive or Kaggle API at runtime.  
- All notebooks keep cell outputs for grading.

---

## Quick start

Open any notebook in Colab and run cells top to bottom.

Minimal steps for Kaggle competitions
1. Mount Drive  

## References I followed

- AutoGluon tabular Kaggle guide  
  https://auto.gluon.ai/stable/tutorials/tabular/advanced/tabular-kaggle.html  
- California housing example  
  https://github.com/autogluon/autogluon/tree/master/examples/automm/kaggle_california_house_price  
- Tabular quick start and in-depth tutorials  
  https://colab.research.google.com/github/autogluon/autogluon/blob/stable/docs/tutorials/tabular/tabular-quick-start.ipynb  
  https://colab.research.google.com/github/autogluon/autogluon/blob/stable/docs/tutorials/tabular/tabular-indepth.ipynb  
- Multimodal tabular  
  https://colab.research.google.com/github/autogluon/autogluon/blob/stable/docs/tutorials/tabular/tabular-multimodal.ipynb  
- Feature engineering  
  https://auto.gluon.ai/stable/tutorials/tabular/tabular-feature-engineering.html
