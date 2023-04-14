# FlightScope LDN: Decoding the Relationship between Time and Price for Flight Data through Data Science

## Project Overview
FlightScope LDN is a data science project aimed at predicting flight ticket prices for flights departing from London to numerous European destinations. The project utilizes various machine learning models, such as linear regression, Lasso regression, Ridge regression, and decision trees, to predict flight ticket prices. The project also includes preprocessing techniques such as one-hot encoding for categorical variables and standardization for numerical variables. 

## Data Collection
The flight data was collected from the Kiwi Tequila Search API, which offers extensive information on flights, routes, and prices. An API key was used to access a vast database of real-time flight data, making it a valuable resource for analysis. The flight data included flights departing from London to numerous European destinations.

## Data Exploration and Analysis
Exploratory data analysis techniques were used to gain insights into the data and identify patterns and trends. The analysis included examining the distribution of flight prices, identifying the most popular airlines and destinations, and analyzing the relationship between flight prices and days left until departure.

## Data Preprocessing
Preprocessing techniques used for this project included:
- One-hot encoding for categorical variables such as 'origin', 'destination', 'airline_name', 'arrival_time_frame', and 'departure_time_frame'
- Standardization for numerical variables such as 'price', 'duration', and 'days_left'
- Splitting the data into training and testing sets

## Machine Learning Models
The project experimented with several supervised machine learning algorithms, including:
- Linear regression
- Lasso regression
- Ridge regression
- Decision trees

The evaluation metrics used for the models included Mean Squared Error (MSE) and R-squared score. The decision trees model was found to be the best choice for the project based on the performance metrics, with the lowest MSE and the highest R-squared score.

## Additional Features
Additional features added to the flight data included:
- 'days_left' feature using the current date of 30/03/2023 to better understand how flight prices change as the departure date approaches
- Mapping out departure and arrival times to desired time frame categories for easier understanding by travelers
- Converting flight data from seconds to hours for simplifying data processing and analysis

## Conclusion
FlightScope LDN is a data science project that utilized various machine learning models, preprocessing techniques, and additional features to predict flight ticket prices departing from London to numerous European destinations. The project found that the decision trees model was the best choice for making accurate predictions. The exploratory data analysis also provided valuable insights into the data and helped to identify important patterns and trends.
