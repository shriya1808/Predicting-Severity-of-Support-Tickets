# Predicting the Severity of Support Tickets from Machine Event Data

## Motivation
Large volumes of customer requests are a common problem for modern service providers, who must respond to them quickly and efficiently to guarantee that customers receive the support they need. One scenario is to determine whether the ticket resolution can be provided remotely, or an onsite intervention is required. Many machine learning classification algorithms have been proposed to tackle this issue. Misclassification not only incurs financial losses for companies but also wastes valuable resources and time for both companies and customers. Historically it has been shown that the point estimation is unreliable in this context. One solution is to measure the uncertainty of predictions, which provides insights into the reliability of classifications, enabling better decision-making.

## Tools and Technology
1. Python 3.9
    - Libraries & Packages: NumPy, Pandas, Matplotlib, Seaborn, Keras, Tensorflow
2. Jupyter Notebook

## Installation
These instructions will get you a copy of the project up and running on your local machine
### Clone
Clone this repo to your local machine using -
```
git clone https://mad-srv.informatik.uni-erlangen.de/MadLab/industry-4.0/seminar-i4.0/ws2024/predicting-the-severity-of-support-tickets-from-machine-event-data.git
```
### Setup
```
conda create --name <env> --file requirements.txt
```

## Run
Run [Data Preprocessing](notebooks/Data_Preprocessing.ipynb), [Monte Carlo Dropout](notebooks/Monte_Carlo_Dropout.ipynb) and [Ensemble Model](notebooks/Ensemble_Model.ipynb) notebooks for the implementation.


Project Organization
------------

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data               <- Data used for modelling.
    │
    ├── presentation       <- Trained and serialized models, model predictions, or model summaries.
    │
    ├── notebooks          <- Jupyter notebooks.
    │
    ├── references         <- literature survey of few research papers before implementation.
    │
    ├── reports            <- Generated analysis as PDF.
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    └── setup.py           <- makes project pip installable (pip install -e .)
