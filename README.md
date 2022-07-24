# ETF_Performance_Analyzer
This application analyzes an exchange-traded fund (ETF) portfolio that contains the following 4 stocks i.e. GDOT, GS, PYPL, and SQ.  The application queries the database to retrieve the open, high, low, close,
volume and daily_returns for these stocks between 2016 to 2020.  The daily returns, annualized returns and cumulative returns are then calculated and plotted for the ETF portfolio.  The application makes use of the Voila library to convert the notebook into a web application so the data maybe visible by others within the organization.

---

## Technologies

This application leverages python 3.7 with the following libraries and packages:

* [pandas](https://github.com/pandas-dev/pandas) - A flexible and power data analysis/manipulation Python library used in financial calculations.

* [sqlalchemy](https://www.sqlalchemy.org/) - A Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL.

* [hvplot](https://pyviz-dev.github.io/hvplot/user_guide/Introduction.html) - Provides a high-level plotting API built on HoloViews that provides a general and consistent API for plotting data.

* [numpy](https://numpy.org/) - A library that contains the fundamental package for scientific computing in Python.

---

## Usage

To use the ETF Performance Analyzer application you must first launch Jupyter Lab by executing the following command within Git Bash:

```python
jupyter lab
```

Within Jupyter Lab you should then be able to run and execute the following notebook:

``` python
etf_analyzer.ipynb
```

To convert the ETF Performance Analyzer notebook into a web application you would execute the following command within Git Bash:

```python
voila etf_analyzer.ipynb
```

As is illustrated below:

![ETF Performance Analyzer Prompts](images/etf_launch_voila.gif)


---

## Contributors

Brought to you by [Drew Herrera](https://www.linkedin.com/in/andrewjherrera).

---

## License

Licensed under the MIT License. Copyright 2022 Drew Herrera.
