# Weather Forecasting Model
A prediction model to determine if it will rain the next day at the given location.

## Dataset
The dataset contains information of a combination of about 65,000 days and locations and their weather conditions. Each instance has 15 attributes including minimum temperature, maximum temperature, wind direction, humidity, temperature, pressure, etc. The data for about 52,000 instances is labeled, and is used to classify the remaining 12,994 unlabeled instances.

## Approach
- Exploratory data analysis
- Data preprocessing (deduplication, handling missing values, dirty data and outliers; data standardization and normalization)
- Classification by creating separate *rain* and *no-rain* clusters using K-means
- Classification using a decision tree classifier

## Results
Algorithm | Accuracy | Recall 
--- | --- | ---
**K-means** | 72.13% | 0.77
**Decision tree** | 76.8% | 0.74
