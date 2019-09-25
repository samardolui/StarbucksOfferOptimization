# StarbucksOfferOptimization
![cover image](images/starbucks_cover_image.jpg)

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Besides the Anaconda distribution of eli5, progressbar and lime libraries need to be installed.
Use below commands to install these two libraries.

`pip install eli5`

`pip install lime`

`pip install progressbar`


## Project Motivation<a name="motivation"></a>

Promotional offers are the order of the day. Almost every corporate organization that sells consumer products does some kind of promotional offers  - be it due to increased competition, or to expand customer base or to generate more revenue. However, sending these offers, costs the organization. It is of utmost importance to maximize the likelihood of success for these offers by devising effective promotional strategies.
In this project, we will analyze 30 days of promotional offers data from Starbucks app to derive business insights about the data and then translate these findings in building an [‘explainable’ machine learning model](https://en.wikipedia.org/wiki/Explainable_artificial_intelligence) that will predict whether or not a customer is going to respond to an offer. The objective is to send offers to only those customers who are more likely to respond and also send offers  having maximum chance of success with that customer.

## File Descriptions <a name="files"></a>

There is a single notebook available here to showcase work related to the above questions.

Data:
* portfolio.json : containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json : demographic data for each customer
* transcript.json : records for transactions, offers received, offers viewed, and offers completed

Images: contains images used in this description file.

## Results<a name="results"></a>

Results are discussed in detail in the [Jupyter Notebook](./Starbucks_Capstone_notebook.ipynb)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credits to [Udacity](https://www.udacity.com/) and Starbucks for the project idea and the dataset.
