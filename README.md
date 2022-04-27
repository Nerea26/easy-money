# Easy Money

![Easy Money](doc/resources/easy-money-logo.PNG "Easy Money")

The final project of the Master of Data Sciences at Nuclio Digital School.
Authors:

- Alfredo Mariño
- Andrea Pilan
- Lorena Checa
- Nerea Domínguez

### Project structure

```
├── README.md
├── data
│   ├── result         <- The data results from the process of clustering and classification.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- Easy money documentations
│
├── notebooks          
│   ├── 1-eda.ipynb    <- EasyMoney EDA
│   │
│   ├── 2-preprocessing-for-clutering.ipynb     <- Preprocessing for clustering process
│   ├── 3-clutering.ipynb                       <- Clustering process
│   │
│   ├── 4-preprocessing-for-classification.ipynb    <- Preprocessing for classification process
│   ├── 5-classification.ipynb                      <- Classification process sample
│   ├── classification                              <- Classification notebooks by product to predict
│   │   ├── Classification__credit_card.ipynb
│   │   ├── Classification__debit_card.ipynb
│   │   ├── Classification__em_acount.ipynb
│   │   ├── Classification__emc_account.ipynb
│   │   ├── Classification__funds.ipynb
│   │   ├── Classification__long_term_deposit.ipynb
│   │   ├── Classification__payroll.ipynb
│   │   ├── Classification__payroll_account.ipynb
│   │   ├── Classification__pension_plan.ipynb
│   │   ├── Classification__securities.ipynb
│   │   └── Classification__short_term_deposit.ipynb
│   │
│   └── 6-recomendation-personalization             <- Unites potential customers and clusters them
│
└── reports
    └── powerbi        <- Clustering graph by powerbi
```