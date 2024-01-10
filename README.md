# House Prices - Advanced Regression Techniques
## Introduction

This project uses advanced regression techniques to predict the sale price of houses for the ames housing data set.
This notebook is used for an ongoing competition on kaggle (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).



<!-- ABOUT THE PROJECT -->
## About The Project
The project is separated into 7 parts.

0. Analysis
   - initial analysis of the data
   - train & test data set are combined for more comprehensive insight
   - various visualisation techniques for in-depth insight
      * heatmap (for missing data)
      * histogram (gave insight over distribution, outliers, skewedness, wrong type allocation)
      * boxplot (better visualisation for outlier)
      * scatterplot (linear relationship to the target 'SalePrice')
1. Data Preparation
   - drop unnecessary features
   - extract target from train set
   - correct wrong data type allocation
2. Preprocessing
   - missing data imputation
3. Feature Engineering
   - transform skewed data
   - encode categorical data
   - normalize numnerical data
   - create sklearn pipeline for all preprocessing & feature engineering steps
4. Model Selection
   - use pycaret for finding best regressors
   - create a stacking regressor consisting of the best regressor
5. Model Training
6. Model Evaluation
7. Model Submission




<!-- ROADMAP -->
## Roadmap

- [ ] improve/try different data imputation technique (currently mean and mode are used), i.e. K-Nearest-Neightbor, or ML models to predict the value
- [ ] generate new features and drop irrelevant ones
- [ ] change model selection approach and in-/exclude (other) regression models
- [ ] hyperparameter tuning

<!-- LIBRARIES -->
## Frameworks & Libraries
- **numpy**: data manipulation
- **pandas**: read and store data
- **seaborn**: visualisation of data
- **sklearn**: manipulate data, i.e. data preprocessing (imputation, scaling, encoding, ...)
- **scipy**: statistical calculations
- **pycaret**: model selection and evaluation


<!-- INSTALLATION -->
## Installation
### Requirements
The notebook needs the packages described above. These come pre-installed on a kaggle notebook environment, pycaret being the exception, which is installed separately in the first line of the notebook to '/kaggle/working/pycaret' to preserve the package on notebook restart.

### Alternative
Alternatively, the dependencies can be installed via the requirements.txt file, which contains all installed packages. </br>
<code>pip install -r requirements.txt</code>

<!-- CONTACT -->
## Contact

Beytullah Ince - [@beytullah-ince][linkedin-url]



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/beytullah-ince

[product-screenshot]: images/screenshot.png




[Numpy-url]: https://numpy.org/
[Numpy.com]: https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white

[Pandas-url]: https://pandas.pydata.org/
[Pandas.com]: https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white

[Seaborn-url]: https://seaborn.pydata.org/
[Seaborn.com]: https://img.shields.io/badge/seaborn-%23013243.svg?style=for-the-badge&logo=seaborn&logoColor=white

[Matplotlib-url]: https://matplotlib.org/
[Matplotlib.com]: https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black

[scikit-learn-url]: https://scikit-learn.org/stable/
[scikit-learn.com]: https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white

[Scipy-url]: https://scipy.org/
[Scipy.com]: https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white
