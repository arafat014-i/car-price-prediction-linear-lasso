# Car Price Prediction Using Linear Regression and Lasso Regression

## Project Overview
This project predicts the selling price of used cars using two machine learning algorithms: Linear Regression and Lasso Regression. It uses vehicle information such as manufacturing year, present price, kilometers driven, fuel type, seller type, transmission, and number of previous owners.

## Dataset
- **Dataset:** Vehicle Dataset from CarDekho
- **Source:** [Kaggle – Vehicle Dataset](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)
- **Target variable:** Selling Price

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Machine Learning Models
1. Linear Regression
2. Lasso Regression

## Model Performance

| Model | Training R² Score | Testing R² Score |
|---|---:|---:|
| Linear Regression | 0.8428 | 0.8709 |
| Lasso Regression | 0.8428 | 0.8709 |

Both models produced identical predictions in the current notebook run. Further verification may be useful before drawing conclusions about their relative performance.

## Project Workflow
1. Load and explore the dataset.
2. Encode categorical variables.
3. Separate features and target variable.
4. Split the dataset into training and testing sets.
5. Train Linear Regression and Lasso Regression models.
6. Evaluate performance using the R² score.
7. Visualize actual versus predicted selling prices.
8. Compare model predictions and performance.

## How to Run
1. Download or clone this repository.
2. Open `car_price_prediction_linear_lasso.ipynb` in Google Colab or Jupyter Notebook.
3. Download the dataset from Kaggle and upload `car data.csv` to your notebook environment.
4. Run the notebook cells in order.

## Author
**Arafat Islam**  
Electronics and Telecommunication Engineering Student  
Chittagong University of Engineering and Technology (CUET)