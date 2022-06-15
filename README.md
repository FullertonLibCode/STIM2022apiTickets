# STIM2022apiTickets
Making springshare tickets via the API using Python

## Requirements
### For those new to python
1. Acquire a API credentials via the springshare web interface.
  * https://YOUR_LIB_ANSWERS_URL/admin/widgets/api/clients
2. [Install Ananconda Distribution](https://www.anaconda.com/products/distribution)
  * `conda install -c anaconda requests`
### For those comforatble with python
  * You will need at a minimum python 3.7+ and the Requests Library `python -m pip  install requests`. You may run the code however you see fit, but in the workshop we will use jupyter, so you may want to use that either natively or through VScode if you want to follow along and help others.

## Additional Setup
So as to not show your api secret in any code examples, it will pull the key from a file .api_info.  This file will not exist and you will have to create it.  It will also be part of the .gitignore since it should not be committed to the public repository we are using.
