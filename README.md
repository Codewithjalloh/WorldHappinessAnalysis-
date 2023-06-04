# WorldHappinessAnalysis
The code starts by importing the necessary libraries: pandas, seaborn, and matplotlib.pyplot.

Next, the data is loaded from a CSV file named 'world_happiness.csv' using the pd.read_csv() function and stored in the DataFrame called df.

The code then answers each of the questions one by one:

Question 1: It finds the country with the highest and lowest happiness score using the idxmax() and idxmin() functions and stores them in the variables max_happiness_country and min_happiness_country.

Question 2: It calculates the correlation between social support and happiness score using the corr() function and stores the result in the variable correlation_social_support.

Question 3: It calculates the average GDP per capita using the mean() function on the 'gdp_per_cap' column and stores the result in the variable average_gdp_per_capita. It also finds the country with the highest and lowest GDP per capita using the idxmax() and idxmin() functions and stores them in the variables country_highest_gdp and country_lowest_gdp.

Question 4: It calculates the correlation matrix using the corr() function on the DataFrame and stores the result in the variable correlation_matrix. Then it identifies the factor (column) that correlates the most with the happiness score by dropping the 'happiness_score' column from the correlation matrix, finding the index of the maximum correlation value, and storing the corresponding column name in the variable most_correlated_factor.

Question 5: It filters the DataFrame to find countries with high GDP per capita but relatively low happiness scores by using boolean indexing. The filtered data is stored in the high_gdp_low_happiness DataFrame.

Question 6: It calculates the correlation between life expectancy and happiness score using the corr() function and stores the result in the variable correlation_life_expectancy.

Question 7: It calculates the average corruption level using the mean() function on the 'corruption' column and stores the result in the variable average_corruption. It also finds the country with the least and most corruption by using the idxmin() and idxmax() functions on the 'corruption' column and stores the corresponding country names in the variables country_least_corrupt and country_most_corrupt.

Question 8: It finds the country with the highest and lowest generosity by using the idxmax() and idxmin() functions on the 'generosity' column and stores the corresponding country names in the variables country_most_generous and country_least_generous.

After answering the questions, the code proceeds to visualize the data using Seaborn and Matplotlib:

Additional Data Visualization: It includes two plots:
Scatter plot: It visualizes the relationship between GDP per capita and happiness score by using the sns.scatterplot() function on the 'gdp_per_cap' and 'happiness_score' columns.
Bar plot: It visualizes the corruption level in different countries by using the sns.barplot() function on the 'country' and 'corruption' columns.
Finally, the plots are displayed using the plt.show() function.

That's the explanation of the code! It loads the data, performs data analysis, and visualizes the results using Seaborn and Matplotlib.
