# Emergency and Retirement Planning

This analysis looks at the current value of cryptocurrencies, stocks, and bonds held to determine if they can be used to fund an emergency account.  

For retirement planning, to scenarios are modeled to determine the range of likely outcomes and if retirement is possible.

## Technologies

This project leverages python 3.7 with the following packages:  

 * [dotenv](https://pypi.org/project/python-dotenv/) - For loading variables into the operating environment from .env files  
 * [requests](https://pypi.org/project/requests/) - For querying APIs  
 * [pandas](https://pandas.pydata.org/) - For analyzing data  
 * [alpaca sdk](https://pypi.org/project/alpaca-trade-api/) - For querying stock and bond prices from [alpaca.markets](https://alpaca.markets/)  
 * [jupyter](https://jupyter.org/) - For an IDE 
 * `MCForecastTools` - For conducting monte carlo simulations

## Installation Guide

Clone the repository and confirm that python 3.7 or greater, pandas, and jupyter are installed.

```python
pip install python-dotenv
pip install requests
pip install pandas
pip install alpaca-trade-api
pip install jupyterlab
```

## Usage

To view the analysis carried out in the notebook click `financial_planning_tools.ipynb` in the file directory of this repo, or click [here](https://github.com/jmischung/Emergency-and-Retirement-Planning/blob/main/financial_planning_tools.ipynb). To interact with the notebook run `jupyter lab` from the directory where `financial_planning_tools.ipynb` is located.  

An API Key and Secret Key from Alpaca are both required if running the notebook locally. Click [here](https://app.alpaca.markets/signup) to create and Alpaca account and request an api key and secret key.

## Contributors

Josh Mischung: [josh@knoasis.io](josh@knoasis.io), [LinkedIn](https://www.linkedin.com/in/joshmischung/)

## License

MIT License

Copyright (c) [2022] [Joshua Mischung]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
