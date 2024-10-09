# Introductory Data Analysis Workshop with Python

This workshop, developed by me, introduces data analysis using **Python**. It covers the key stages of data analysis: **data manipulation**, **visualization**, and **modeling**. Through practical exercises, participants will learn how to work with data, extract valuable insights, create visual representations, and build predictive models.

## Learning Units

### 1. **Data Analysis**
In this unit, participants will learn how to write Python programs using mathematical operators and basic methods to generate **descriptive statistics** and perform fundamental calculations. Techniques for data manipulation will be explored to extract relevant information from raw datasets.

**Key commands**:
- `import pandas as pd`
- `data.describe()`
- `data.mean()`

### 2. **Data Visualization**
This unit focuses on creating **informative graphs** using the **Seaborn** library. Participants will learn how to generate custom visualizations, adjusting parameters based on their analytical needs. Effective data visualization is essential for interpreting results and making informed decisions.

**Key commands**:
- `import seaborn as sns`
- `sns.histplot(data)`
- `sns.scatterplot(x='column1', y='column2', data=data)`

### 3. **Modeling**
In the final unit, participants will implement a **linear regression model** in Python. We will use **scikit-learn** to train the model and visualize the results with `regplot` graphs to interpret the relationships between variables. This technique is crucial for understanding patterns and making predictions.

**Key commands**:
- `from sklearn.linear_model import LinearRegression`
- `model = LinearRegression()`
- `sns.regplot(x='column1', y='column2', data=data)`

## Platforms and Tools Used

Throughout the workshop, the following platforms and tools were used:

- **[Google Colaboratory](https://colab.research.google.com/)**: A cloud-based environment for writing and executing Python code.
- **[Anaconda](https://www.anaconda.com/)**: A Python distribution that includes tools for data analysis.
- **[Visual Studio Code](https://code.visualstudio.com/)**: A code editor that simplifies development with Python and other technologies.

## Requirements

To follow this workshop, make sure to have the following libraries installed:

```bash
pip install pandas
pip install seaborn
pip install scikit-learn
```
## Project Structure

The project is divided into several **Jupyter notebooks**, containing the code and exercises for each learning unit. As you progress through the workshop, you will be able to:

1. **Load and analyze data** using the **Pandas** library.
2. **Visualize results** with interactive graphs using **Seaborn**.
3. **Create and evaluate a linear regression model** to understand relationships between variables.

## Contributions

If you have any suggestions, improvements, or contributions, feel free to open a **pull request**. I am open to collaborations that enhance this workshop and make it more useful for those looking to learn data analysis.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

