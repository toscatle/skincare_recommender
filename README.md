# Skincare Recommender
Author: Tosca Le

<img src="images/skincare_cover_photo.jpeg">

###### image source: 

## Overview
This project explores a dataset of specific types of skincare products from Sephora to build a recommendation system for customers looking to find different products and develop a skincare routine suited for their needs. Through the implementation of different collaborative filtering approaches, personalized recommendations can be obtained for individual customers.   
***

## Business Problem
As one of largest cosmetics retailer, Sephora is hoping to find new ways to attract and interact with customers who might find skincare and the number of products out there overwhelming. Building recommendations tailored to customers' preferences will help not only their shopping experiences, but hopefully improve the likelihood of finding beneficial products.
***

## Data & EDA
Credits to Anastasia Gorina for the dataset and can be found [here](https://github.com/agorina91/final_project/blob/master/Jupyter_Notebook_and_CSV/skindataall.csv). The resulting dataset contains over 8000 entries. Below are distributions of applicable features.
*insert images
***

## Methods
Through the different approaches of collaborative filtering, iterations of memory-based and model-based techniques are examined through similarity metrics and RMSE. The dataset was split into training and test sets for model validation.
***

## Results
The KNNBaseline method with pearson correlation had the lowest RMSE with a mean test RMSE of 1.19 after cross-validation. SVD had a very similar RMSE after performing a grid search to tune hyperparameters.
***

## Conclusions

***

## Next Steps

***

### For More Information
Please review my full analysis in my [Jupyter Notebook](./skincare_recommender_notebook.ipynb) or [presentation]().

The dataset used in this analysis can be found at

For any additional questions, please contact me at **toscatle@gmail.com**.
***

### Repository Structure
```
├── images
├── .gitignore
├── LICENSE                          
├── README.md 
├── skincare_recommender_notebook.ipynb  
├── tbd                                
└── tbd                              
```
