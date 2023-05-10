# Cars4U-Project
## Data Description
- TThe data contains the different attributes of used cars sold in different locations. The detailed data dictionary is given below
- Data Dictionary
S.No.: Serial number
Name: Name of the car which includes brand name and model name
Location: Location in which the car is being sold or is available for purchase
Year: Manufacturing year of the car
Kilometers_driven: The total kilometers (a unit used to measure length or distance) driven in the car by the previous owner(s)
Fuel_Type: The type of fuel used by the car (Petrol, Diesel, Electric, CNG, LPG)
Transmission: The type of transmission used by the car (Automatic/Manual)
Owner: Type of ownership
Mileage: The standard mileage offered by the car company in kmpl or km/kg
Engine: The displacement volume of the engine in CC
Power: The maximum power of the engine in bhp
Seats: The number of seats in the car
New_Price: The price of a new car of the same model in dollars
Price: The price of the used car in dollars
### Objective
- Come up with a pricing model that can effectively predict the price of used cars and can help the business in devising profitable strategies using differential pricing. For example, if the business knows the market price, it will never sell anything below it.
### Steps to follow 
- Create a python3 virtual environment, run the command and activate it
1. Launch the jupyter notebook
2. Install and import the required packages
3. Explore the dataset
4. Perform the data-preprocessing
5. Carry out feature engineering
6. Before training the model, I select the label from the features
7. Split the data into training data and test data
8. Scale the training data to have the mean of 0 and standard deviation of 1
9. Next is to train and evaluate the model performance using the metrics from scikit-learn
10. Lastly carry out the validation using the test data.
### Conclusion
An R-squared of 74% and 73% on both training and test data were obtained, even with the regularisation strength of both ridge and lasso regressions.
This means that, 73% of the time, the model will correctly predict the price of the used cars.
