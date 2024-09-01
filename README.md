# Title

LLMs for Forecasting Stock Movemment in Healthcare Sector

## Description

This study investigates the utilisation of news data to forecast stock movements in the healthcare sector by employing Large Language Models (LLMs). More precisely, it explores the use of pre-trained and fine-tuned LLMs to forecast the weekly movement of stock prices for the top 25 tickers in this sector. The compared models include BERT, RoBERTa, DistilBERT, DistilRoBERTa, and FinBERT. 

## Getting Started

### Dependencies

* WRDS (Wharton Research Data Services) Access: Required for data retrieval.

### Executing program

The notebooks are structured as follows:

* **Data Collection and Pre-processing**
  1. Data_Preparation.ipynb
     
* **LLMs Modelling**
  *  Scenario 1: Pre-Trained Models
      1. Generate_Embeddings_Pre_Trained_Models.ipynb
      2. Training_&\_Prediction_(Pre_Trained).ipynb
     
  * Scenario 2: Fine-Tuned Models
      1. Learning_Hyperparameter_Optimisation.ipynb
      2. Training_&\_Prediction_(Fine_Tuned).ipynb

* **Portfolio Analysis**
  1. Portfolio_Analysis_Pre_Trained.ipynb
  2. Portfolio_Analysis_Fine_Tuned.ipynb

* **Portfolio Analysis + Transaction Cost**
  1. Portfolio_Analysis_+_Transaction_Cost_Pre_Trained.ipynb
  2. Portfolio_Analysis_+_Transaction_Cost_Fine_Tuned.ipynb

* **EDA**
  1. Data_Visualisation_ERP.ipynb

## Authors

Gusti Kresna
gusti.kresna10@gmail.com


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
