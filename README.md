# Medical Insurance Cost Prediction

## Project Overview
The Medical Insurance Cost Prediction project aims to predict the cost of medical insurance for individuals based on various features such as age, sex, BMI, number of children, smoking status, and region. The project leverages machine learning techniques to build a predictive model that can provide insights and forecasts for insurance costs, helping both insurers and individuals make informed decisions.

## Features
- **Age**: Age of the individual.
- **Sex**: Gender of the individual (male/female).
- **BMI**: Body Mass Index, a measure of body fat based on height and weight.
- **Children**: Number of children covered by the insurance.
- **Smoker**: Smoking status of the individual (yes/no).
- **Region**: The region in which the individual resides.
- **charges**: Medical insurance cost billed by the insurance company

## Project Structure
- `Model/`: 
  - **Medical cost prediction.ipynb**: Jupyter notebook for data exploration, visualization, model development, and evaluation.
  - **DATA AUGMENTATION.ipynb**: Jupyter notebook for data augmentation.
- `PPT/`: Contains presentation slides.
- `Report/`: Contains the project report.
- `data/`: Contains the dataset 'insurance.csv' and the newly generated data 'newdata(After data augmentation).csv' using data augmentation.
- `README.md`: Project overview and documentation (this file).

## Usage

### Data Preprocessing
- Preprocess the dataset to handle missing values, duplicated values, encode categorical variables, and normalize/standardize features. This step is crucial to ensure that the data is in a suitable format for model training.

### EDA
- Perform Exploratory Data Analysis (EDA) to identify patterns and key insights in the data. This helps in understanding the underlying structure and relationships between variables.

### Model Training
- Train the predictive model using various machine learning algorithms such as Linear Regression, Decision Trees, Random Forest, XgBoost, etc. Experiment with different algorithms to compare their performance on the dataset.

### Model Evaluation
- Evaluate the model’s performance using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² score. These metrics will help assess how well the model predicts insurance costs.

### Prediction
- Use the trained model to predict insurance costs for new data. The model should generalize well to unseen data, providing accurate cost predictions based on the features provided.

## Conclusion
In this project, I utilized various machine learning regression algorithms to build models for predicting medical insurance costs to compare their performance. I performed data augmentation due to the limited number of samples available. However, the presence of categorical columns like gender posed challenges during the data augmentation process, leading to models that did not perform well on the augmented dataset. 


## Contact

If you have any questions or feedback, please feel free to contact me at rakeshnemu237@gmail.com.
