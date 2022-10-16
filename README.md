# Financial Simulations with Alpaca API

This repo displays a prototype banking application that performs two seperate actions:

1) Provides users with the ability to access to their monthly budgets. 
2) Provides forecast for a retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds.

---

## Technologies

This project leverages python 3.7 with the following packages:

* [os] - Creates/ removes directories and retrieves contents from within our folders

* [requests](https://github.com/psf/requests) - Makes an API request 

* [json](https://github.com/nlohmann/json) -  Transfers data from our API that can be translated into text 

* [pandas](https://github.com/pandas-dev/pandas) - For cleaning and filtering the data.

* [dotenv](https://github.com/motdotla/dotenv) - Reads key-value pairs from our .env file and sets them as environment variable

* [alpaca_trade_api](https://github.com/alpacahq/alpaca-trade-api-python) - The API we are using

* [MCForecastTools](https://github.com/Anu86/MCForecastTools) - Creates our Monte Carlo Simulation

---

## Installation Guide

Before running the application first install the following dependencies.

```python
  conda install -c anaconda requests
  conda install -c jmcmurray json
  pip install python-dotenv
  pip install alpaca-trade-api
```

---

## Usage

To use the financial simulations application, simply clone the repository and create a new_folder to save your **financial_planning_tools.ipynb** . Navigate to that folder within your terminal, and type the following :

```new_folder
   jupyter lab 
```

Upon launching the financial simulations application, you will be able to view the total value of the member's portfolio, along with a projection of what their portfolio will look like in 10+ years. 

<img width="1440" alt="Screen Shot 2022-10-16 at 9 48 10 AM" src="https://user-images.githubusercontent.com/105071493/196047741-0498dd0a-1123-4c55-bfa9-b56c05e39bf1.png">

<img width="1440" alt="Screen Shot 2022-10-16 at 9 43 54 AM" src="https://user-images.githubusercontent.com/105071493/196047580-995710ce-41be-4085-9d2d-fd7db7a40f76.png">

---

## Contributors

Name: Sterling Davis 
Email: sterlingdayvis@gmail.com
LinkedIn: www.linkedin.com/in/sterlingdavis1

---

## License

MIT




