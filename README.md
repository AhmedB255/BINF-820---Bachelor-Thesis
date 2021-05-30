# Data-Mining-for-Cloud-Security-Bachelor-Project
My repository that contains my practical work related to my bachelor thesis.

Name: Ahmed Baher <br>
University: German University in Cairo <br>
Major: Business Informatics <br>

<h1>Project Objectives:</h1>

The goal is to determine if feature selection can improve anomaly detection accuracy. Anomaly detection is performed using machine learning classification algorithms.

<h1>Tools and Algorithms Used:</h1>

Tools: Python, Pandas, NumPy, Scikit-learn, and Jupyter Notebook.

Feature selection algorithm used: <a href="https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.f_classif.html">f_classif</a>

Classification algorithms used: 
<ul>
  <li><a href="https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html">DecisionTreeClassifier</a></li>
  <li><a href="https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.GaussianNB.html">GaussianNB</a></li>
</ul>

Analysis was performed on two datasets: the GUC dataset, which comes from the university's cloud, and the <a href="https://www.unb.ca/cic/datasets/nsl.html">NSL-KDD dataset</a>.

3-fold cross-validation was performed on the GUC dataset while 5-fold cross-validation was performed on the NSL-KDD dataset.

Hyperparameter tuning algorithm used: <a href="https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html">GridSearchCV</a>

<h1>Project Conclusions:</h1>

Feature selection improved the anomaly detection accuracy for both datasets, but the accuracy rates of the GUC dataset were horrid because the dataset was insufficient in terms of the number and type of features.
