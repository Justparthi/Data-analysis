# Data Analysis of Nobel Prize Research

This repository contains Python scripts for analyzing data related to Nobel Prize winners and their research. The analysis is based on publicly available data and utilizes Python's powerful data analysis libraries.


### Running the Analysis

You can run the analysis using Python locally or via a Jupyter notebook. Alternatively, you can try out the code directly in a Google Colab notebook:

- **Google Colab Notebook**: [Interactive Analysis Example](https://colab.research.google.com/drive/1nXL94XnYAC_eJRGBH4Qy_jYgbAGv7CaG#scrollTo=3uN3wN5sIqvH)

### Libraries Used

#### 1. Pandas
- **Purpose**: Pandas is used for data manipulation and analysis, allowing you to handle structured data such as CSV files.
- **Documentation**: [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- **Key Functions**:
  - `read_csv()`: Load data from a CSV file.
  - `DataFrame.head()`: Display the first few rows of a DataFrame.
  - `DataFrame.groupby()`: Group data based on specific columns, such as prize category or year.
  - `DataFrame.describe()`: Generate descriptive statistics on Nobel Prize data.

#### 2. Matplotlib
- **Purpose**: Matplotlib is a versatile plotting library used for creating static, animated, and interactive visualizations.
- **Documentation**: [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- **Key Functions**:
  - `pyplot.plot()`: Generate line plots to show trends over time.
  - `pyplot.bar()`: Create bar charts to compare Nobel Prizes awarded by category or country.
  - `pyplot.title()`, `pyplot.xlabel()`, `pyplot.ylabel()`: Add titles and labels to your plots.

#### 3. Seaborn
- **Purpose**: Seaborn builds on Matplotlib and simplifies the creation of complex statistical plots.
- **Documentation**: [Seaborn Documentation](https://seaborn.pydata.org/)
- **Key Functions**:
  - `seaborn.barplot()`: Create bar plots to analyze the distribution of Nobel Prizes by category.
  - `seaborn.heatmap()`: Visualize correlations between different variables, such as country and prize count.
  - `seaborn.boxplot()`: Visualize the distribution of Nobel Prizes over the years.

### Data Sources

The analysis is based on data related to Nobel Prize winners and their research, which can be sourced from official Nobel Prize databases and other related resources.

- **Download Example Data**: [Nobel Prize Data](#) *(Insert the link to your data source)*







