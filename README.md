# Pipeline Project

This project involves creating a machine learning model pipeline.

Data must be appropriately handled in a pipeline to predict whether an item is recommended by a customer based on their review. The data includes numerical, categorical, and text data.

## The Data
The dataset has been anonymized and cleaned of missing values.

There are 8 features for to use to predict whether a customer recommends or does not recommend a product. The Recommended IND column gives whether a customer recommends the product where 1 is recommended and a 0 is not recommended. This is your model's target/

The features can be summarized as the following:

Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.
Age: Positive Integer variable of the reviewers age.
Title: String variable for the title of the review.
Review Text: String variable for the review body.
Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.
Division Name: Categorical name of the product high level division.
Department Name: Categorical name of the product department name.
Class Name: Categorical name of the product class name.
The target:

Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.

## Getting Started

To start, clone this repo on your local machine

### Dependencies

1. All libraries required are in the requirements.txt file
2. Create a virtual environment and install all libraries


## File Structure

1. The data used is in the reviews.csv file
2. The codes are in the dsnd_pipeline.ipynb. Run this file to build the pipelines and train the model


## Credits

1. Udacity
2. Author: Kikelomo Obayemi
