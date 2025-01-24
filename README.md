# Predicting Housing Prices Using Machine Learning Models

## Description
This project aims to predict housing prices using advanced machine learning models. The dataset used is from Kaggle's **House Prices: Advanced Regression Techniques** competition. The focus of this project was on **data preprocessing**, **feature engineering**, and optimizing multiple models to achieve accurate predictions.

## Workflow
1. **Exploratory Data Analysis (EDA)**
2. **Data Preprocessing and Feature Engineering**
3. **Model Training and Hyperparameter Tuning**
4. **Model Evaluation**
5. **Submission and Ensemble Techniques**

## Technologies Used
- **Python**: Core programming language.
- **Jupyter Notebook**: For project development.
- **scikit-learn**: Machine learning library.
- **XGBoost**: Boosting algorithm.
- **pandas, numpy**: Data manipulation and numerical computations.
- **plotly**: Data visualization.

## Dataset Description
- **Source**: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- **Size**: 1460 training examples and 291 testing examples.
- **Features**: 79 explanatory variables describing every aspect of residential homes.
- **Target Variable**: `SalePrice` (log-transformed for better model performance).

## Results
### Model Performance
| Model                  | RMSE on Validation Data |
|------------------------|--------------------------|
| Random Forest          | 0.1504                  |
| XGBoost                | 0.1378                  |
| MLP (Neural Network)   | 0.1268                  |
| Averaged Ensemble      | 0.1322                  |
| Stacking Ensemble      | 0.1322                  |

### Highlights
- **Best Individual Model**: XGBoost (RMSE: 0.1378)
- **Best Ensemble Model**: Averaged Ensemble (RMSE: 0.1322)
- **Stacking Model RMSE**: 0.1322 (Final Test Data RMSE)

The iterative process of model improvements, from initial results to fine-tuned models, demonstrates practical machine learning skills and problem-solving abilities.

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/Atsalas/Predicting-Housing-Prices-Using-Machine-Learning-Models.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Predicting-Housing-Prices-Using-Machine-Learning-Models
    ```

3. Install the required dependencies. Make sure you have Python 3.7+ and Jupyter Notebook installed:
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

5. Run the notebook `Predicting Housing Prices Using Machine Learning Models.ipynb` to execute the entire workflow.

---

## Contact

For any questions, suggestions, or collaborations, feel free to reach out via:

- **GitHub**: https://github.com/Atsalas
- **Email**: mailto:atsalasv@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/atsalas/

---

## Acknowledgments

- Dataset provided by [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).
- Inspiration and resources from online tutorials and the Kaggle community.
