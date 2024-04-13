# Voices-of-Walmart

#this is the README file that contains a description of the project.

This project takes a dataset of Walmart Employee Reviews and performs the following:
- EDA (Cleaning, filtering, grouping, RegEx) and Visualization:
    - group and filter the dataset to categorize years into 'pre-covid', 'covid', and 'post-covid' eras to plot a grouped + stacked bar chart titled 'Employee Ratings by Covid Era and Employment Status'
    - clean the 'location' column to display only the state abbreviation (derived from state name), and use this information and a json file of the US map to plot a map showcasing the average ratings in every state
    - filter out stopwords from the 'reviews' column to make a word cloud of all the commonly used words in over 200,000 walmart employee reviews
- Regression:
    - calculate the average ratings of employess in various states over time.
    - use this information to plot a linear regression model of average and predicted ratings from 2011 to 2023
    - make it more user friendly by asking for an input (the state abbreviation), and be prepared to plot the curve and data points for any state
- Bootstrapping
- Classification
     - decision tree using gini index
- Feature Engineering 
    - matched minimum wage with year and state from 2011 to 2020

Future Improvements:
- clean the 'review' column before creating the word cloud to keep only adjectives for better inference
- 