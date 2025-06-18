# HSI Project: Carbohydrate Content Prediction in Millets

This project aims to predict the carbohydrate content in millets using hyperspectral imaging data and various machine learning techniques. Hyperspectral imaging captures detailed spectral information across different wavelengths, which is then analyzed using machine learning models to estimate the carbohydrate content.

## 📁 Project Structure

- `Hyperspectral_data_millets_11_varieties.csv`: Dataset containing hyperspectral data for 11 millet varieties.
- `mean_spectra.ipynb`: Script to compute and visualize mean spectra for each millet variety.
- `project_LR.ipynb`: Implementation of Linear Regression model for prediction.
- `project_RF.ipynb`: Implementation of Random Forest model for prediction.
- `project_RL.ipynb`: Implementation of Ridge Regression model for prediction.
- `project_SVR.ipynb`: Implementation of Support Vector Regression model for prediction.
- `project_XGB.ipynb`: Implementation of XGBoost model for prediction.
- `project_plsr.ipynb`: Implementation of Partial Least Squares Regression model for prediction.

## ⚙️ Requirements

To run the notebooks, you'll need the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`

You can install these dependencies using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
