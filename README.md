# California_housing_dataset_Visualization

Analyzed the California housing dataset with Python, uncovering key insights and solutions that highlight housing trends.

<img src="https://tse2.mm.bing.net/th?id=OIP.HhQ3elOu2Jy0RfpFSRl3dAHaE6&pid=Api&P=0&h=180">

## Abstract
  The California housing dataset, sourced from the 1990 census, comprises 20,640 entries and 10 columns. Each entry corresponds to a distinct housing block in the state. The dataset encompasses various attributes such as population, number of households, latitude, longitude, house age, median income, house value, total rooms, total bedrooms, and ocean proximity. Notably, ocean proximity stands as the sole categorical column, with five categories: island, inland, near bay, near ocean, and <1H ocean. The dataset's dependent variable is house value.

  The dataset was imported and managed using the Pandas library, and visualized through Seaborn and Matplotlib in Python. Notably, the total bedrooms column exposed 207 missing values.

### Key Insights:
  Analyzing the house age provided insights into the construction years, enabling the graphing of house counts per year using Seaborn's countplot. Surprisingly, a recurring wave-like pattern emerged, with peaks around 1946, 1954-55, 1964-65, 1974, and 1985, reflecting the cyclical nature of the real estate industry. Intriguingly, a surge in house construction occurred in 1938, followed by a notable decline in 1939, possibly linked to the onset of World War I. This observation underscores the dataset's capacity to unveil historical nuances within the housing landscape.

  While the maximum age recorded in the dataset is 52, it's essential to note that these values represent the median age of individual housing blocks. Consequently, there exist houses within these blocks that surpass the age of 52, emphasizing the presence of older dwellings in the dataset

<a href="https://ibb.co/TKyzbvB"><img src="https://i.ibb.co/WDCSPxW/house-built-year.png" alt="house-built-year" border="0"></a>



## Questions addressed:
1. What is the average median income of the data set and check the distribution of data using appropriate plots. Please explain the distribution of the plot.
2. Draw an appropriate plot to see the distribution of housing_median_age and explain your observations.
3. Show with the help of visualization, how median_income and median_house_values are related?
4. Create a data set by deleting the corresponding examples from the data set for which total_bedrooms are not available.
5. Create a data set by filling the missing data with the mean value of the total_bedrooms in the original data set.

6. Write a programming construct (create a user defined function) to calculate the median value of the data set wherever required.

7. Plot latitude versus longitude and explain your observations.

8. Create a data set for which the ocean_proximity is ‘Near ocean’.

9. Find the mean and median of the median income for the data set created in question 8.

10. Please create a new column named total_bedroom_size. If the total bedrooms is 10 or less, it should be quoted as small. If the total bedrooms is 11 or more but less than 1000, it should be medium, otherwise it should be considered large.



