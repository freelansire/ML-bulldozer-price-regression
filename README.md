## Predicting the Sale Price of Bulldozers using Machine Learning
This project applies machine learning techniques to predict the future sale price of bulldozers, based on their characteristics and historical sales data.

#### 1. Problem Definition
The core objective is to predict the future sale price of a bulldozer given its features and previous sales records.

> Question:
How well can we predict the future sale price of a bulldozer, based on previous examples of how much similar bulldozers have been sold for?

#### 2. Data
The dataset is sourced from the Kaggle competition: Bluebook for Bulldozers.
> https://www.kaggle.com/c/bluebook-for-bulldozers/data

The data consists of three main files:

* Train.csv: The training dataset.
* Valid.csv: The validation dataset.
* Test.csv: The test dataset.

#### 3. Evaluation

The model will be evaluated using the `RMSLE (Root Mean Squared Logarithmic Error)` between the actual and predicted sale prices.

The goal is to minimize this error metric.

The expected format for output files:

* Must have a header: SalesID, SalePrice.
> Contain two columns:
* SalesID: The Sales ID for the validation set in sorted order.
* SalePrice: Your predicted sale price for that bulldozer.

#### 4. Features
Kaggle has provided a detailed data dictionary describing each feature. You can view the full data dictionary here: Data Dictionary (Google Sheets).
> https://docs.google.com/spreadsheets/d/18ly-bLR8sbDJLITkWG7ozKm8l3RyieQ2Fpgix-beSYI/edit?usp=sharing

#### Viewing the Notebook
You can view and interact with this notebook online without having to download it. There are two options for this:

#### Using NBViewer

NBViewer renders Jupyter notebooks directly in your browser.
Go to nbviewer and enter the URL of the notebook to view it.

#### Using Google Colab

Colab allows you to run Jupyter notebooks in the cloud for free.
Steps:

* Open Google Colab.
* Click on "File" > "Open Notebook".
* Select the "GitHub" tab and enter the repository URL.
* Click on the notebook file to open and run it in Colab.

#### Getting Started Locally
To run the notebook locally:

* Clone the repository.
* Install the required dependencies using pip install -r requirements.txt.
* Run the Jupyter notebook.

#### License
This project is open-source under the MIT License.
