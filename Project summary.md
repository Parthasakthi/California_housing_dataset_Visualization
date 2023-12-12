# California_housing_dataset_Visualization

Analyzed the California housing dataset with Python, uncovering key insights and solutions that highlight housing trends.

<img src="https://tse2.mm.bing.net/th?id=OIP.HhQ3elOu2Jy0RfpFSRl3dAHaE6&pid=Api&P=0&h=180">

## Dataset:
  The California housing dataset, sourced from the 1990 census, comprises 20,640 entries and 10 columns. Each entry corresponds to a distinct housing block in the state. The dataset encompasses various attributes such as population, number of households, latitude, longitude, house age, median income, house value, total rooms, total bedrooms, and ocean proximity. Notably, ocean proximity stands as the sole categorical column, with five categories: island, inland, near bay, near ocean, and <1H ocean. The dataset's dependent variable is house value.

  The dataset was imported and managed using the Pandas library, and visualized through Seaborn and Matplotlib in Python. Notably, the total bedrooms column exposed 207 missing values.

### Key Insights:
  - Analyzing the median house age provided insights into the construction years, enabling the graphing of house counts per year using Seaborn's countplot. Surprisingly, a recurring wave-like pattern emerged, with peaks around 1946, 1954-55, 1964-65, 1974, and 1985, reflecting the cyclical nature of the real estate industry. Intriguingly, a surge in house construction occurred in 1938, followed by a notable decline in 1939, possibly linked to the onset of World War II. This observation underscores the dataset's capacity to unveil historical nuances within the housing landscape.

  - While the maximum age recorded in the dataset is 52, it's essential to note that these values represent the median age of individual housing blocks. Consequently, there exist houses within these blocks that surpass the age of 52, emphasizing the presence of older dwellings in the dataset

<a href="https://ibb.co/TKyzbvB"><img src="https://i.ibb.co/WDCSPxW/house-built-year.png" alt="house-built-year" border="0"></a>
- The kdeplot reveals a concentration of house construction in the near bay and island areas from 1938 to 1940, a surge in inland housing during the 1970s, and an elevated number of houses near the ocean in the mid-20th century.
- 
  <a href="https://ibb.co/SVDw7Pv"><img src="https://i.ibb.co/2c03YyK/kde-plot.png" alt="kde-plot" border="0"></a>
  
- A robust positive correlation emerges between the number of rooms and population, aligning with typical expectations.

- Furthermore, a positive correlation is observed between house value and median income, indicating that individuals with higher incomes tend to inhabit more expensive homes—an association that intuitively aligns with socioeconomic patterns.
  
- House values exhibit a strong correlation with location, particularly indicating that residences near the ocean command higher values, and this association extends to income, with higher incomes observed in proximity to the ocean.






