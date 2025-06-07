# Carbon Footprint Estimator (Regression Task)

##  Description
This is a machine learning project built as part of the internship screening process at Jayadhi Ltd. The goal is to estimate a person’s weekly carbon footprint (in CO₂ kg) based on their lifestyle inputs like diet, transport, and electricity usage.

##  Dataset Used
I created a custom dataset in CSV format with 60 rows, where each row contains:
- Type of diet (veg/non-veg)
- Kilometers traveled per week (by car/bike/public transport)
- Electricity usage (kWh/week)
- Weekly carbon footprint (target column)

##  Approach
- Loaded and cleaned the dataset using `pandas`
- Built a simple regression model using `scikit-learn` (`LinearRegression`)
- Evaluated model using Mean Squared Error (MSE)
- Visualized predictions vs actual values using `matplotlib`

##  Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn


##  How to Run
1. Open the Jupyter Notebook in Google Colab or locally
2. Run all cells in order
3. Modify the input values to test your own footprint prediction

##  Output Example
Sample output:  
> "Your estimated weekly CO₂ footprint is: **37.4 kg**"

##  Author
Tanmay Kulkarni  
BTech Metallurgy & Materials Engineering  
NIT Srinagar
