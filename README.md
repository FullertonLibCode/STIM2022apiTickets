# STIM2022apiTickets
Making springshare tickets via the API using Python

## Requirements
1. Acquire a API key via the springshare web interface.
2. [Install Ananconda Distribution](https://www.anaconda.com/products/distribution)
  * `conda install -c anaconda requests`
  * For demo purposes we will use Jupyter Lab, but if you are comfortable with python already you can install 3.7+ and the Requests Library `python -m pip  install requests` and run the code however you see fit.

## Additional Setup
So as to not show your api secret in any code examples, it will pull the key from a file .api_info.  This file will not exist and you will have to create it.  It will also be part of the .gitignore since it should not be committed to the public repository we are using.
