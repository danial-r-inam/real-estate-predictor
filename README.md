# real-estate-predictor

# RealAgents House Sales Project

## Overview

The project's primary objective was to optimize house listing prices by predicting sale prices based on house characteristics. The data provided includes historical sales in a specified metropolitan area. Key features include house ID, city, sale price, sale date, months listed, number of bedrooms, house type, and area.

## Project Structure

### Task 1: Missing City Data Analysis
- Analyzed the 'house_sales.csv' file.
- Identified and quantified missing 'city' values.
- The resulting data was stored in `missing_city`.

### Task 2: Data Cleaning
- Cleaned and preprocessed data from 'house_sales.csv'.
- Addressed missing values and anomalies across various columns as per given criteria.
- Produced a cleaned dataframe, `clean_data`, matching the specified structure.

### Task 3: Bedroom Price Analysis
- Investigated the impact of the number of bedrooms on house price.
- Created `price_by_rooms` dataframe showing average sale price and variance, grouped by bedroom count.

### Task 4: Baseline Model for Price Prediction
- Developed a baseline model using 'train.csv'.
- Predicted sale prices on 'validation.csv'.
- Generated `base_result` dataframe with `house_id` and predicted `price`.

### Task 5: Comparative Model Development
- Created an alternative model using the same training data.
- Performed predictions on the validation set.
- Produced `compare_result`, similar to `base_result`, for performance comparison.

## Technologies Used
- Data analysis and cleaning: Pandas, NumPy
- Model building: Sklearn

## Contributors
- Danial Rashid Inam

*This project was a practical application of data science techniques in the real estate domain, aiming to enhance the efficiency and accuracy of house pricing for RealAgents.*
