# meteorite-classification
Used machine learning to classify meteoritic presolar grains and compare to science classification. Python.

The Machine Learning models used for this analysis include: XGBoost, Random Forest Classifier, Decision Tree, k Nearest Neighbors, Logistic Regression, Deep Learning and SVM. For each model, a variety of isotope combinations were analyzed inlcuding: carbon 12/13, silicon 29/28, silicon 30/28, nitrogen 14/15, and aluminum 26/27.

Scientists have classified these presolar grains, and the goal of this project was to check how close machine learning could get at making those same classifications. The top 6 model-isotope combinations are Random Forest Classifier and XGBoost using the carbon, silion, and nitrogen isotopes, just carbon and silicon istopes, or just carbon and nitrogen isotopes. 

If you would like to install these files, you will need Jupyter Notebook to open the ipynb files, which contain all of the machine learning models in Python code.

Data Source: https://presolar.physics.wustl.edu/presolar-grain-database/
