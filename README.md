# Using K-Means for USDA Food Project (Clustering)

## Introduction
An exploratory analysis of USDA foods using nutrients to see how accurately foods can be clustered. I am hoping to find foods that are not normally grouped, falling into similar groups. This could suggest alternative foods for different types of diets. For example, a vegan might find a particular plant food grouped with animal products and could mean that they could have similar benefits. The csv file was generated from files download from FoodCentral website. The data was used to build an app that is not yet published. However, because the data was stored in a MySQL database, a Python script was used to connect to the database and retrieve and format the data in a csv file.

## Project Overview
- Exploratory Data Analysis and Feature Scaling
- Create K-Means Cluster Model
- Find optimum number of cluster by plotting intertia
- Use PCA and t-SNE for dimensionality reduction


## Resources
- Python Version: 3.9.12
- Packages: Numpy, Pandas, Seaborn, Matplotlib, sklearn


## Model Building

The optimal K was calculated by plotting the inertia.
The K-Means model was used with K=20.


## Results

It was observed that the clusters were basically aligned with how groups of food are organized for the most part. For example, sugary foods were grouped together, meat products were also grouped together. If you observe cluster 3, even though you have quite a number of meat products you also have some seeds, greens and beans. These meat products are different from cluster 8, where the meat products seems to be more of the fattier type. Since these leaner meats are clustered with seeds, greens and beans, it confirms as suggested by science that some plant-based foods can be good replacement for meat, at least in some aspects.