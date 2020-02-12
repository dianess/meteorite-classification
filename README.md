# Machine Learning Analysis for Meteoritic Presolar Grain Classification
Analyzed machine learning models to classify meteoritic presolar grains compared to science classifications. Python.

The Machine Learning models used for this analysis include: XGBoost, Random Forest Classifier, Decision Tree, k Nearest Neighbors, Logistic Regression, Deep Learning, and SVM. For each model, a variety of isotope combinations were analyzed inlcuding: carbon 12/13, silicon 29/28, silicon 30/28, nitrogen 14/15, and aluminum 26/27.

Scientists have classified these presolar grains using stellar models, and the goal of this project was to check how close machine learning models could get at making those same classifications. The top 6 model-isotope combinations are Random Forest Classifier(RFC) and XGBoost using the carbon, silion, and nitrogen isotopes, just carbon and silicon istopes, or just carbon and nitrogen isotopes. <img src="/machine learning files/assets/images/Top_6_ML_Model_Isotope_Combinations.jpg" alt="Top 6 ML Model Isotope Combinations">

Based on the number of records in each of those top isotope combination categories, we recommend using the carbon & silicon isotopes with either Random Forest Classifier or XGBoost. <img src="/machine learning files/assets/images/Top6combos_number_of_records.jpg" alt="Top 6 combinations: Number of Records">

If you would like to install these files, you will need Jupyter Notebook to open the ipynb files, which contain all of the machine learning models in Python code. To view the Prezi project presentation, click: [Machine Learning Analysis for Meteoritic Presolar Grain Classification](https://prezi.com/view/lsPIz30stoGdFEnZHKBo/). If you don't already have a Prezi account, you can create a free basic account at: [Prezi Basic Account](https://prezi.com/pricing/?click_source=logged_element&page_location=header&element_text=get_started)

Data Source: [Presolar Grain Database](https://presolar.physics.wustl.edu/presolar-grain-database/)
