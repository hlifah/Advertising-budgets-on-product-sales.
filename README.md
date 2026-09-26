Dataset Overview and Summary StatisticsThe dataset contains 200 observations detailing advertising budgets (in thousands of dollars) across three media channels (TV, Radio, and Newspaper) and the corresponding product Sales (in thousands of units).   
Missing Values: None.   
Key Statistical Highlights:
TV Advertising: Mean = 147.04, Min = 0.70, Max = 296.40   
Radio Advertising: Mean = 23.26, Min = 0.00, Max = 49.60   
Newspaper Advertising: Mean = 30.55, Min = 0.30, Max = 114.00  
Sales: Mean = 14.02, Min = 1.60, Max = 27.00   
Multiple Linear Regression ResultsUsing a standard 80-20 train-test split (random_state=42), a Multiple Linear Regression model was fit on the features (TV, Radio, Newspaper) to predict Sales:
Model Coefficients:
TV: 0.0447Radio: 0.1901
Newspaper: 0.0028
Intercept: 2.9791
Performance Metrics (Test Set):
$R^2$ Score: \approx 0.899 (indicating that ~89.9% of the variance in sales is explained by the advertising budgets)
Root Mean Squared Error (RMSE): \approx 1.78

<Figure size 750x250 with 3 Axes><img width="741" height="251" alt="image" src="https://github.com/user-attachments/assets/e0738e33-377e-4075-904f-e885ab62aa77" />
