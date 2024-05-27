<a name="readme-top"></a>

<div align="center">
  <h1><b>SALES FORECAST</b></h1>
</div>


 TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📗 Table of Contents](#-table-of-contents)
- [Time Series Analysis ](#Time-Series-Analysis-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
  - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Install](#install)
    - [Usage](#usage)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [🙏 Acknowledgments ](#-acknowledgments-)
  - [📝 License ](#-license-)
## Project Description
<!-- PROJECT DESCRIPTION -->
# Time Series Analysis <a name="about-project"></a>

**Time Series Analysis** This project focuses on enhancing Corporation Favorita's inventory management through accurate product demand forecasting. Leveraging machine learning models and historical sales data, we aim to optimize inventory levels, minimize stockouts, and maximize profitability. By integrating advanced forecasting techniques into Corporation Favorita's operations, we seek to ensure always right quantity of product in stock. Through this data-driven approach, we aim to provide Corporation Favorita with actionable insights to make informed inventory management decisions and maintain a competitive edge in the retail industry.

Features
| Feature    | Definition                |
|------------|---------------------------|
|Date        |day which sale has been made   |
|Store_nbr | Unique identifier of a store where a sale has been done|
|Family | type of a product that is sold |
|Sales | The total amount of a particular family product|
|Onpromotion | number of family products that were on promotion |
|Transaction | sales made on a specific date |
|City | location of the store |
|State |State which store is located  |
|Cluster |stores grouped with similarity|
|oil price |cost of oil |
|Type |the type of day can be holiday,bridge,workday |
|Transfer |a day that was supposed to be holiday but the holiday moved to another day |
|Locale |location a holiday is being calebrated  |
|locale_name |The name of location |
| Description |describes the day or holiday |

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>GUI</summary>
  <ul>
    <li><a href="">Streamlit</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="">Microsoft SQL Server</a></li>
  </ul>
</details>

<details>
<summary>Language</summary>
  <ul>
    <li><a href="">Python</a></li>
  </ul>
</details>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- Features -->

## Key Features <a name="key-features"></a>

- **Business understanding: Understanding the project and formualating the hypotheis to test together with business questions to answer that will help in the analysis**
- **Data collection : Gathered comprehensive data on corporation favorita sales behaviour and factors influencing them**
- **Data Integration: Combine data from multiple sources such as SQL databases, csv files and GitHub repositories to create a unified dataset for analysis**
-**Exploratory Data Analysis(EDA): Examining and understanding the structure, patterns, and relationships within the dataset. This involved summary statistic, univariate analysis , bivariate analysis, outlier detection and handling missing values**
 **Data Cleaning: preparing the unified data ready for analysis**
 - **Visualizations: Using matplotlib and seaborn to create visually appealing charts, graphs and heatmaps to help answer the business questions**
 - **Answering Business questions: Using visualizations to answer business questions that help in analysing the dataset**
 
- **Hypothesis Testing: Testing formulated Hypothesis about the relationship between items onpromotion and sales. Performing statistical analysis to test this hypothesis using the T-test test method**
- **Data preparation : Transforming the dataset into a format suitable for training and evaluating ML models. Encompassing a range of tasks to improve the quality, consistency, and relevance of the data, ultimately leading to better model performance and insights. It involes checking if the data is balanced, feature engineering, data transformation, data splitting , constructing pipelines.**
- **Modelling : Creating mathematical representations (models) that learn patterns and relationships from the dataset in order to make predictions on whether a customer will churn or not.Data is trained both when balanced and unbalanced. The models trained include;statistical models such as Autoregression(AR),AutoRegression Intergrated Moving Average (ARIMA),(SARIMA)Seasonal AutoRegression Intergrated Moving Average and traditional statistical models such as LinearRegression and XGBClassifier**

- **Hyperparameter Tuning : Hyperparameters are parameters whose values are set before the learning process begins. They control aspects such as the complexity of the model and its capacity to learn.Hyperparameter tuning helps improve model performance by finding the optimal settings.It prevents overfitting or underfitting of the model by adjusting hyperparameters.Proper tuning can lead to better generalization on unseen data.The steps include Use cross-validation to evaluate the performance of different hyperparameter settings.Consider the computational cost when choosing a tuning technique.Start with a coarse search space and refine it based on initial results.Monitor the performance metrics closely to avoid overfitting to the validation set.**

- **saving the models: After training a machine learning model, it's important to save it for future use or deployment. Saving the model allows you to reuse it without the need to retrain from scratch.Joblib: Use libraries like Joblib or Pickle to serialize Python objects, including trained models, to disk.**

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>


To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- Python
- Jupyter lab
-  Data on sales from Corporation Favorita retail store


### Setup

Create a new repository on github and copy the URL
Open Visual Studio Code and clone the repository by pasting the URL and selecting the repository destinatination

Create a virtual environment

```sh

python -m venv venvv

```

Activate the virtual environment

```sh
    venv/Scripts/activate
```


### Install

Here, you need to recursively install the packages in the `requirements.txt` file using the command below 

```sh
   pip install -r requirements.txt
```
## Usage
To run the project, execute the following command:
```sh
    jupyter notebook Time_Series.ipynb

```
- jupyter notebook will open the specified notebook
- users can explore the code, execute cells, and interact with the project's analysis and visualization

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

🕵🏽‍♀️ **Felix Kwemoi Motonyi**

- GitHub: [GitHub Profile](https://github.com/Felo10coder/git-and-github)
- Twitter: [Twitter Handle](https://x.com/Felo109?t=QQ7Gv-Lj-t6EyLIxYaJFGg&s=09)
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/felo10)
- Medium: [Medium Profile]()
- Email: [email](felixkwemoi7@gmail.com)
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcomed!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project kindly show some love, give it a 🌟 **STAR** 🌟

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>
I would like to thank my team members for their efforts and support in this project. Starting with my team leader Dennis Gitobu, Joy Koech , Loyce Zawadi, Davis Kazungu and Evalyne Nyawira.
I would like to also thank all the free available resource made available online

<p align="right">(<a href="#readme-top">back to top</a>)</p>