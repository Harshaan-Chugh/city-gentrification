# city-gentrification
Predicting Gentrification in Cities using Logistic Regression

**Problem Statement**

In recent years, urban areas throughout the world have experienced rapid, concentrated development, a process known as gentrification. While this process has many benefits to the urban area, there are many unintended consequences when it occurs unexpectedly and can harm its residents.
Our goal was to help identify occurences of gentrification so that governments can take action accordingly

**Data**

* Data was collected for 13 distinct features and 1 label.
* After training the logistic regression model, features were combined/deleted to 10 
* The final features were population density, median household income, average 1 bedroom apt rent, poverty rate, average age, and racial demographic percentages
* Data was labeled 0 or 1 for gentrified/not
* Data Sources:
 - https://www.census.gov/data.html
 - https://www.zumper.com/rent-research
 - https://worldpopulationreview.com/us-cities

**Model Building**
- Started with using the Random Forest Algorithm
- After training the model and combining features it was found that the model was overfitting and lacked accuracy(60%)
- Switched the algorithm to Logistic Regression and found higher accuracy
- Split data 80-20 train-test

**Results & Future Improvements**
Got good model prediction accuracy of roughly 72%
Potential Improvements:
- Collect data for more cites
- Larger data sets for training and testing 
- Collect data from multiple years (ex: 2017 - Present)
- Give us rate of change instead of just current data (more accurate)
- Race Interpretation
- Potential Model Bias removal

