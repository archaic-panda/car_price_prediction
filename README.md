The dataset used in this analysis contains information about car prices and their associated features. Here's a brief overview of the dataset:

Columns: The dataset consists of several columns including:

* Make: The brand or manufacturer of the car (e.g., Toyota, Honda, Ford).
* Model: The specific model of the car (e.g., Camry, Civic, F-150).
* Year: The manufacturing year of the car.
* Mileage: The total mileage (in miles) of the car.
* Condition: The condition of the car, categorized as Excellent, Good, or Fair.
* Price: The price of the car.
* Size: The dataset contains a certain number of rows, each representing a unique car entry, and a set of columns describing various attributes of the cars.

* Conclusion:
* The logic is the higher the closer to 1 the r2 score is the better and the lower the mse is the better
* XGBRegressor Performed the best with a better r2_score (0.998) and mse value (138) than the rest
* SVR performed the worst, the model is not usable
