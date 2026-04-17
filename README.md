# Experiment 17: Statistical and Specialized Data Visualization Techniques

# 1. Aim
To study and implement advanced statistical data visualization techniques using Python libraries such as Matplotlib and Seaborn in order to identify outliers, analyze correlations, and represent the distribution and composition of complex datasets.

# 2. Introduction to Libraries
Pandas (pd): Used for organizing and managing data in the form of DataFrames, making it easier to perform statistical operations such as correlation analysis.
Matplotlib (plt): A fundamental plotting library that provides complete control over the design and customization of visualizations.
Seaborn (sns): A high-level visualization library built on Matplotlib, designed to create informative and visually appealing statistical plots with minimal effort.
NumPy (np): Used for numerical computations and handling arrays, often required for generating and manipulating sample data.

# 3. Common Utility Functions
plt.figure(figsize=(w, h)) – Sets the size of the visualization for better clarity
plt.title() – Adds a title to the plot
plt.xlabel() / plt.ylabel() – Labels the axes
plt.show() – Displays the final output

# 4. Procedure and Visualization Techniques

Step 1: Box Plot (Outlier Detection)
Purpose: To summarize data using key statistical measures and identify outliers.
Function Used: sns.boxplot()
Description: The boxplot represents the distribution of data through five main values: minimum, first quartile, median, third quartile, and maximum. Data points lying beyond the whiskers are considered outliers.

# 
Step 2: Heatmap (Correlation Analysis)
Purpose: To visualize relationships between multiple numerical variables.
Function Used: sns.heatmap()
Description: A correlation matrix is first computed using df.corr(). The heatmap then represents these values using color gradients. Strong correlations are indicated by more intense colors, and numerical values can be displayed within the cells for clarity.

# 
Step 3: Bubble Plot (Multivariable Visualization)
Purpose: To represent three variables within a single plot.
Function Used: plt.scatter()
Description: Similar to a scatter plot, but the size of each point varies according to a third variable. This allows simultaneous visualization of relationships among three different parameters.
# 
Step 4: Pie Chart (Composition Analysis)
Purpose: To show how different categories contribute to a whole.
Function Used: plt.pie()
Description: Data is represented as proportional slices of a circle. Each slice corresponds to a category, and percentage values can be displayed for better understanding.
#
Step 5: Violin Plot (Distribution Analysis)
Purpose: To provide a detailed view of data distribution by combining boxplot and density information.
Function Used: sns.violinplot()
Description: The shape of the violin reflects the distribution density of the data. Wider sections indicate a higher concentration of values, offering deeper insight compared to standard boxplots.

# 5. Conclusion
This experiment demonstrates the importance of advanced visualization techniques in statistical data analysis. Tools such as boxplots and heatmaps help in identifying outliers and understanding relationships between variables, while plots like violin and bubble charts provide deeper insights into data distribution and multi-variable interactions. Seaborn, along with Matplotlib, enables the creation of effective and visually appealing statistical representations with ease.
