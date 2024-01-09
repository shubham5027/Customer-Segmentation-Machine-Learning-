 Customer Segmentation using Machine Learning (KMeans Clustering)
==============================================================

This repository contains the code and resources for a customer segmentation project using KMeans clustering algorithms. The project includes:

* Data preprocessing
* KMeans clustering
* Evaluation and visualization
* Deployment of a web application using Streamlit

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

Web Application
---------------

![Screenshot 2024-01-09 225746](https://github.com/shubham5027/Customer-Segmentation-using-Machine-Learning/assets/132193443/ba621cb7-bc9f-4c24-b970-97932961b262)
![Screenshot 2024-01-09 224151](https://github.com/shubham5027/Customer-Segmentation-using-Machine-Learning/assets/132193443/7715787b-568c-431e-a4c3-7c7ea4806699)
application allows the user to:


EDA on the Data
---------------
![newplot (4)](https://github.com/shubham5027/Customer-Segmentation-using-Machine-Learning/assets/132193443/51b671e0-1e8b-4ac6-a3f1-2d72106207ea)
![newplot (1)](https://github.com/shubham5027/Customer-Segmentation-using-Machine-Learning/assets/132193443/5730d159-c598-48f9-aa4b-f1ae109b0394)
![newplot (2)](https://github.com/shubham5027/Customer-Segmentation-using-Machine-Learning/assets/132193443/4ac930f4-6aad-40ae-8e03-e80d89ededd9)
![newplot](https://github.com/shubham5027/Customer-Segmentation-using-Machine-Learning/assets/132193443/a9bc5bf5-eaf3-46f1-93b4-2a83c488d26e)
![newplot (3)](https://github.com/shubham5027/Customer-Segmentation-using-Machine-Learning/assets/132193443/d292c7f3-f0fa-48d2-bf42-a191f1c14bab)





References
----------

* [KMeans Clustering in Scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
* [Streamlit Documentation](https://docs.streamlit.io/)

License
-------

This project is licensed under the MIT License. See the `LICENSE` file for details.  
