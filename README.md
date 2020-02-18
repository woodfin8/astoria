# astoria
Astoria Advisers Files

This application extracts US Economic data from [FRED](https://fred.stlouisfed.org/) via the Python API [fredapi](https://github.com/mortada/fredapi).

To run this program, you will need an api key which can be [found here](https://research.stlouisfed.org/docs/api/api_key.html)
Save the api key as "key" in a seperate config.py file

Running FREDapi.ipynb will grab the desired indicators combine them with the indicator's info, create a 'change' column and save the data to a csv in the 'data' folder. 
