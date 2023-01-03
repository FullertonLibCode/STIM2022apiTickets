# STIM2022apiTickets
Making springshare tickets via the API using Python

## Requirements

### For Everyone
* Acquire a API credentials via the springshare web interface.
  * https://YOUR_LIB_ANSWERS_URL/admin/widgets/api/clients
    1. Under the API Authentication tab, click the "Add New Application" button.
    2. Provide a name and description at your discretion, they will not actually be used in the code.
    3. Check the "Create Access" checkbox at a minimum. We won't use View or Udpate in what we cover, so if you want the minimum go with create only.
    4. Make a note of the Client ID and Client Secret. You will need to put the secret in a text file named ".api_info" and Client ID will be used in directly in the code.

### For those new to python

* [Install Ananconda Distribution](https://www.anaconda.com/products/distribution)
  * Install additional library: `conda install -c anaconda requests`
  
### For those comforatble with python
  * You will need at a minimum python 3.7+ and additional Libraries `python -m pip  install requests` & `python -m pip  install pandas`. You may run the code however you see fit, but in the workshop we will use jupyter, so you may want to use that either natively or through VScode if you want to follow along and help others `python -m pip install jupyterlab`.

## Additional Setup
So as to not show your api secret in any examples, the code will pull the key from a file .api_info.  This file will not exist and you will have to create it.  It will also be part of the .gitignore since it should not be committed to the public repository we are using.
