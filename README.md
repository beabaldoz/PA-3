# PA-3
## PROBLEM 1 ## 
### Using knowledge obtained from the experiment and demonstrations: 
### a. Load the corresponding .csv file into a data frame named cars using pandas;
### b. Display the first five and last five rows of the resulting cars 

#### import pandas as pd - function used to access panda library
#### cars = pd.read_csv('cars.csv') - function to read the imported file 'cars.csv'
#### to get the first five cars, I used the function '.head()'.
#### on the other hand, to get the last five cars, I used the function '.tail()'.

## PROBLEM 2 ##
### Using the dataframe cars in problem 1, extract the following information using subsetting, slicing and indexing operations.
### a. Display the first five rows with odd-numbered columns (columns 1, 3, 5, 7...) of cars.
### b. Display the row that contains the ‘Model’ of ‘Mazda RX4’.
### c. How many cylinders (‘cyl’) does the car model ‘Camaro Z28’ have?
### d. Determine how many cylinders (‘cyl’) and what gear type (‘gear’) do the car models ‘Mazda RX4 Wag’, ‘Ford Pantera L’ and ‘Honda Civic’ have.

#### In problem 2, I mostly used subsetting because the problem mostly asks for certain elements.
#### Odd cars - in this problem, I used the '.iloc' function and typed in the numbers of the odd-numbered columns being asked.
#### Display the row that contains the 'model' of 'Mazda RX4' - I used the '.loc' function in this one and entered the row number where the Mazda RX4 is.
#### How many cylinders does the car model 'Camaro X28' have? - To print the cyl of this car, I also used the '.loc' function and typed in the number of the row where the car is located and the name of the column being asked, which is cyl.
#### For the last question, I also used the same technique as the previous ones, only this time, more things are being asked. 
