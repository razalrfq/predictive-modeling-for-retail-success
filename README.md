📊 Sales Prediction using DataCo Supply Chain Dataset

This project is based on predicting sales using the **DataCo Supply Chain Dataset**.
The main aim of this project is to study the factors that influence sales and build a machine learning model that can predict future sales more accurately. 
This helps businesses understand trends and make better decisions.

➤ Dataset Information

The dataset contains supply chain and sales data with more than **180,000 records** and **53 columns**. It includes useful information such as:

- Product Price  
- Quantity Ordered  
- Discount  
- Shipping Details  
- Customer Data  
- Order Information  

This large dataset is helpful for analyzing real business sales patterns.


➤ Data Preprocessing

Before training the model, the data was cleaned and prepared properly. The following steps were done:

- Missing values were handled  
- Outliers were removed using IQR method  
- Date columns were converted into correct format  
- Categorical values were encoded  
- Numerical data was scaled when needed  

New Features Created:

Some new columns were created to improve prediction accuracy:

- Delivery Delay  
- Shipping Duration  
- Order Month  
- Order Weekday  
- Total Order Value  


➤ Models Used

Different machine learning models were tested:

- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  

These models were compared to find the best result.


 ➤ Model Training

To improve performance and avoid overfitting:

- K-Fold Cross Validation was used  
- RandomizedSearchCV was used for tuning parameters  
- Model complexity was controlled  
- Different models were compared  


 ➤ Evaluation Methods

The model performance was checked using:

- R² Score  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  


➤ Key Learnings

This project helped in understanding:

- Importance of data cleaning  
- Feature selection methods  
- Avoiding data leakage  
- Cross-validation techniques  
- Improving model accuracy  


➤ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib  
- Seaborn  


➤ Final Result

The final model was able to predict sales based on previous supply chain data with good accuracy. This project shows how machine learning can be used in real business problems.


➤ Author

Razal Rafeeque Kottat

