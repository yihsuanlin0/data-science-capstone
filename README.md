# data-science-capstone
## introduction

##excutive summary
The research attempts to identify the factors for a successful rocket landing. To make this determination, the following methodologies where used:

Collect data using SpaceX REST API and web scraping techniques
Wrangle data to create success/fail outcome variable
Explore data with data visualization techniques, considering the following factors: payload, launch site, flight number and yearly trend
Analyze the data with SQL, calculating the following statistics: total payload, payload range for successful launches, and total # of successful and failed outcomes
Explore launch site success rates and proximity to geographical markers
Visualize the launch sites with the most success and successful payload ranges
Build Models to predict landing outcomes using logistic regression, support vector machine (SVM), decision tree and K-nearest neighbor (KNN)

## data collection 
Request data from SpaceX API (rocket launch data)
Decode response using .json() and convert to a dataframe using .json_normalize()
Request information about the launches from SpaceX API using custom functions
Create dictionary from the data
Create dataframe from the dictionary
Filter dataframe to contain only Falcon 9 launches
Replace missing values of Payload Mass with calculated .mean()
Export data to csv file
