[![LinkedIn][adam-linkedin-shield]][adam-linkedin-url]
[![LinkedIn][swas-linkedin-shield]][swas-linkedin-url]
[![LinkedIn][navneeth-linkedin-shield]][navneeth-linkedin-url]
[![MIT License][license-shield]][license-url]

<br />
<div align="center">
  <a href="https://github.com/AdamSkog/Datathon-DataMed">
    <img src="imgs/datamed.png" alt="Logo">
  </a>

<h2 align="center">Datathon 2025</h2>

  <p align="center">
    Team DataMed's submission for the DubsTech Datathon 2025.
    <br />
    <a href="https://github.com/AdamSkog/Datathon-DataMed/issues">Report Bug</a>
    ·
    <a href="https://github.com/AdamSkog/Datathon-DataMed/pulls">Request Feature</a>
  </p>
</div>

---

## Table of Contents
- [Table of Contents](#table-of-contents)
- [About the Project](#about-the-project)
  - [Built With](#built-with)
- [Contact](#contact)

## About the Project
Team DataMed's submission for the 2025 Datathon hosted by DubsTech at the University of Washington. We have chosen the prompt of **Health: Drug Overdose in USA** on the Machine Learning track.

### Summary of the Project

We focused on Health: Analyzing the New York State of Health as our prompt for the Datathon. We used the dataset provided by the prompt to analyze the data and build multimple machine learning models to:

- Predict the following for a Specific Hospital and DRG Type for the next 1 year:
  - Discharges
  - Median Costs
  - Median Charges
- Predict the total expected discharges for each DRG Type for the State of New York
- Predict the mean cost of a discharge using features like:
  - Hospital
  - APR DRG code
  - Severity of illness
  - Year
  - Medical/Surgical classification.


#### 1. `meancost.ipynb`
**Mean Cost Prediction of Inpatient Discharges**
This notebook predicts the *Mean Cost* of inpatient hospital discharges based on historical data. It uses features like Facility Name, APR DRG Code, Severity of Illness, and Medical/Surgical Description. Several machine learning models are trained, including Linear Regression, Decision Trees, Random Forests, and XGBoost, to identify trends and minimize discharge costs. The goal is to deliver actionable insights for hospital cost management.

#### 2. `drg_discharge_pred.ipynb`
**DRG Discharge Volume Prediction for New York State**
This notebook forecasts the *total expected discharges* for each Diagnosis-Related Group (DRG) type across New York State. After cleaning and preparing the dataset, it applies machine learning models such as Random Forest, Prophet, XGBoost, and LightGBM. Model performance is evaluated using MAE and RMSE to select the best discharge prediction approach, supporting resource and capacity planning in healthcare settings.

#### 3. `1yearpred.ipynb`
**One-Year Forecast of Hospital Metrics**
This notebook predicts three key metrics, *Discharges*, *Median Costs*, and *Median Charges*, for the next year for a specific hospital and DRG type. Time series models (ARIMA and Auto-ARIMA) are employed to understand historical trends and generate reliable forecasts. These insights assist hospitals in strategic planning, budgeting, and operational management.



### Built With
[![Python][python-shield]][python-url]
[![pandas-shield]][pandas-url]
[![Scikit-Learn][sklearn-shield]][sklearn-url]

## Contact
- Adam Skoglund - @AdamSkog - ajskog@uw.edu
- Swastik Singh - @swassingh - swas@uw.edu
- Navneeth Dhamotharan - @Navneethd8 - nd17@uw.edu


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[license-shield]: https://img.shields.io/badge/MIT-red?style=for-the-badge&label=LICENSE
[license-url]: https://github.com/AdamSkog/Scoliosis-Xray-Classification/blob/main/LICENSE

[python-shield]: https://img.shields.io/badge/Python-%233776AB?style=for-the-badge&logo=Python&labelColor=black
[python-url]: https://python.org

[pandas-shield]: https://img.shields.io/badge/-Pandas-blue?style=for-the-badge&logo=pandas&labelColor=black
[pandas-url]: https://pandas.pydata.org/

[sklearn-shield]: https://img.shields.io/badge/-Scikit--Learn-blue?style=for-the-badge&logo=scikit-learn&logoSize=auto&labelColor=black
[sklearn-url]: https://scikit-learn.org/

[adam-linkedin-shield]: https://img.shields.io/badge/adam-linkedin-blue?style=for-the-badge&logo=linkedin&link=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fadam-skoglund%2F
[adam-linkedin-url]: https://linkedin.com/in/adam-skoglund

[swas-linkedin-shield]: https://img.shields.io/badge/swas-linkedin-blue?style=for-the-badge&logo=linkedin&link=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fswassingh%2F
[swas-linkedin-url]: https://www.linkedin.com/in/swassingh/

[navneeth-linkedin-shield]: https://img.shields.io/badge/navneeth-linkedin-blue?style=for-the-badge&logo=linkedin&link=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fnavneeth-dhamotharan%2F
[navneeth-linkedin-url]: https://www.linkedin.com/in/navneeth-dhamotharan/