# Predicting Gentrification in Cities using Logistic Regression

## Problem Statement

In recent years, urban areas worldwide have seen rapid, concentrated development, known as gentrification. While this can benefit cities, it can also harm residents when it occurs unexpectedly. Our goal is to predict instances of gentrification to enable proactive governmental intervention.

## Data

- Collected data for 13 features and 1 label.
- Reduced features to 10 after model training.
- Final features: population density, median household income, average rent for a 1-bedroom apartment, poverty rate, average age, and racial demographic percentages.
- Labels: gentrified (1) or not (0).
- Data Sources:
  - Census data: [link](https://www.census.gov/data.html)
  - Rent statistics: [Zumper](https://www.zumper.com/rent-research)
  - Demographic data: [World Population Review](https://worldpopulationreview.com/us-cities)

## Model Building

- Initially used Random Forest algorithm.
- Switched to Logistic Regression due to overfitting and low accuracy (~60%).
- Data split: 80% training, 20% testing.

## Results & Future Improvements

- Achieved approximately 72% prediction accuracy.
- Potential Improvements:
  - Expand data collection to include more cities.
  - Increase dataset size for better training and testing.
  - Incorporate multi-year data (e.g., 2017-present) for trend analysis.
  - Consider dynamic metrics (rate of change) rather than static data.
  - Address potential biases in the model, particularly related to racial demographics.
