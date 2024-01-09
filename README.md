 Customer Segmentation using Machine Learning 
===============================================


Run This App
------------
https://customer-segmentation-machine-learning-webapp-vjvaefg8lhaf7zn2.streamlit.app/

This repository contains the code and resources for a customer segmentation project using KMeans clustering algorithms. The project includes:

* Data preprocessing
* KMeans clustering
* Evaluation and visualization
* Deployment of a web application using Streamlit


Data Preprocessing
-----------------
  
![newplot (4)](https://github.com/shubham5027/Customer-Segmentation-Machine-Learning-Webapp/assets/132193443/462a43ef-45a5-4bd6-a77b-c8401ab6c4b4)
![newplot](https://github.com/shubham5027/Customer-Segmentation-Machine-Learning-Webapp/assets/132193443/b758a966-2ec6-435c-acc0-94c500490096)
![newplot (1)](https://github.com/shubham5027/Customer-Segmentation-Machine-Learning-Webapp/assets/132193443/575c3384-6c35-4ebe-8bf5-25c12b59c4b0)
![newplot (2)](https://github.com/shubham5027/Customer-Segmentation-Machine-Learning-Webapp/assets/132193443/4ed2687c-ecab-49c7-9802-2bfa17b028ac)
![newplot (3)](https://github.com/shubham5027/Customer-Segmentation-Machine-Learning-Webapp/assets/132193443/a201b6dc-54f2-4dee-a410-88b017294e95)


Algorithms Analysis
-----------------

![algorithm](https://github.com/shubham5027/Customer-Segmentation-Machine-Learning-Webapp/assets/132193443/61310abc-7a51-4041-ada2-f52e63d50c3b)



Deployment on Web
-----------------

![Screenshot 2024-01-09 225746](https://github.com/shubham5027/Customer-Segmentation-Machine-Learning-Webapp/assets/132193443/6433787d-06da-4c41-8be3-8400cbf27c30)
![Screenshot 2024-01-09 224213](https://github.com/shubham5027/Customer-Segmentation-Machine-Learning-Webapp/assets/132193443/5e61a9a3-332f-4845-8a3a-2adf783d7bad)
![Screenshot 2024-01-09 225752](https://github.com/shubham5027/Customer-Segmentation-Machine-Learning-Webapp/assets/132193443/643ed342-516f-40f8-906d-88ff32a66bae)
![Screenshot 2024-01-09 232002](https://github.com/shubham5027/Customer-Segmentation-Machine-Learning-Webapp/assets/132193443/69b7046e-a1fe-4937-8459-8530cda3430a)


Prerequisites
-------------

* Python 
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Streamlit

Getting Started
---------------

1. Clone this repository:

```bash
git clone https://github.com/shubham5027/customer-segmentation.git
```

2. Navigate to the project directory:

```bash
cd customer-segmentation
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Run the Google Colab `Customer_Segmentation.ipynb` to perform data preprocessing, clustering, and evaluation.

5. To deploy the web application, run:

```bash
streamlit run _app.py
```

Data Preprocessing
------------------

The data preprocessing step involves:

* Loading the customer dataset
* Cleaning the data
* Feature engineering
* Scaling the data

KMeans Clustering
-----------------

KMeans clustering algorithm is used to segment the customers into different groups based on their features. The algorithm is run with different values of `k` to select the optimal number of clusters.

Evaluation and Visualization
----------------------------

The evaluation step involves:

* Visualizing the clusters in 2D and 3D
* Calculating the Within-Cluster Sum of Squares (WCSS) for each value of `k`
* Selecting the optimal number of clusters based on the WCSS plot

References
----------

* [KMeans Clustering in Scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
* [Streamlit Documentation](https://docs.streamlit.io/)

License
-------

This project is licensed under the MIT License. See the `LICENSE` file for details.  
