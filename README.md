
# Fintech Finder

[
<img width="861" alt="Screen Shot 2021-08-02 at 12 48 01 PM" src="https://user-images.githubusercontent.com/80833988/127915431-d96967d9-439a-4249-a09a-d7caa7df12e8.png">
](url)



📌 Challenge 19

> "In this Challenge, I assumed the role of blockchain lead developer, working for a fintech startup. My goal is to integrate the Ethereum blockchain network into Fintech Finder application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency. "


## Table of content
- [Overview of the project and project goals](https://github.com/nataliaburrey/blockchain_based_ledger#overview-of-the-project-and-project-goals) 
- [Project steps](https://github.com/nataliaburrey/blockchain_based_ledger#project-steps)
- [Software version control](https://github.com/nataliaburrey/blockchain_based_ledger#software-version-control)
    - [Libraries](https://github.com/nataliaburrey/blockchain_based_ledger#libraries)
    - [Work with GitHub](https://github.com/nataliaburrey/blockchain_based_ledger#work-with-github)
    - [How to install](https://github.com/nataliaburrey/blockchain_based_ledger#how-to-install)
    - [Run Streamlit](https://github.com/nataliaburrey/blockchain_based_ledger#run-streamlit)
- [Helps recruiters](https://github.com/nataliaburrey/blockchain_based_ledger#helps-recruiters)
- [License](https://github.com/nataliaburrey/blockchain_based_ledger#license)



## Overview of the project 

In this Challenge, I was task to  complete the code that enables customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, we assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.

To complete this Challenge, I am using two Python files:
1. [fintech_finder.py]()  contains the code associated with the web interface of the application. The code included in this file is compatible with the Streamlit library. 

2. [crypto_wallet.py]() contains the Ethereum transaction functions. By using import statements, I integrate the crypto_wallet.py Python script into the Fintech Finder interface program that is found in the fintech_finder.py file. 


Integrating these two files allow the user to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via Ethereum’s Kovan testnet.

## Project goals

1. Generate a new Ethereum account instance by using your mnemonic seed phrase (which you created earlier in the module).

2. Fetch and display the account balance associated with your Ethereum account address.

3. Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

4. Digitally sign a transaction that pays a Fintech Finder candidate, and send this transaction to the Kovan testnet.

5. Review the transaction hash code associated with the validated blockchain transaction.

6. Once you receive the transaction’s hash code, you will navigate to Kovan’s Etherscan (Links to an external site.) website to review the blockchain transaction details 


## Project steps

The steps for this Challenge are divided into the following sections:

### Step 1: Import Ethereum Transaction Functions into the Fintech Finder Application

Import generate_account, get_balance, and send_transaction from the crypto_wallet.py file. (10 points)

Call the generate_account function and store the account object. (10 points)

Call the get_balance function and pass it the Ethereum account.address. (10 points)



### Step 2: Sign and Execute a Payment Transaction

Calculate the transaction’s total wage. (10 points)

Call the send_transaction function and pass it the account, candidate_address, and wage parameters. (5 points)

Return the transaction hash from the send_transaction and display it on the application’s web interface. (5 points)



### Step 3: Inspect the Transaction on Etherscan

Send a transaction using the Fintech Finder app, and then use the returned transaction hash to verify the transaction on Etherscan. In the README.md file of your GitHub repository for this Challenge assignment, include a screenshot of the provided transaction details. (10 points)

In your README.md file, provide screenshots from Etherscan that show the sender’s address balance and history, and the recipient's address balance and history. (10 points)



## Software version control


### Libraries 

##### Following libraries were imported


```
# Import the required libraries and dependencies

import streamlit as st
from dataclasses import dataclass
from typing import Any, List

```
*  Pandas - is a software library designed for data analytics that makes it easier to work with data from practically any type of file. Pandas supplies powerful tools for working with time data in particular, and time is a key aspect of financial analysis. Analysts typically compare and measure financial assets—from single stocks to large portfolios—across time.
* Streamlit- is an open-source app framework for Machine Learning and Data Science teams.
* Dataclasses-a utility tool to make structured classes specially for storing data. These classes hold certain properties and functions to deal specifically with the data and its representation.
* Typing-provides runtime support for type hints. The most fundamental support consists of the types Any, Union, Tuple, Callable, TypeVar, and Generic.
* Datetime-supplies classes for manipulating dates and times.

[
<img width="658" alt="Screen Shot 2021-08-02 at 1 05 59 PM" src="https://user-images.githubusercontent.com/80833988/127917395-947eaeaf-7ade-471f-84ec-e96e3c8eafa4.png">
](url)


 
### Work with GitHub
* Repository created on GitHub
* Files were  committed using command line
* Our repository is organized, and includes Resources folder with CSV  project files, 
* Jupyter Notebook with code runs without errors.
* Answers on nesassary questions are included

### How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone 
```

now you can find repo on your desktop




### Run streamlit

1. In the terminal, navigate to the repository folder

2. In the terminal, run the Streamlit application by running the command

```
streamlit run 

```



## Helps recruiters

The project was created in collaboration with Berkeley Fintech Bootcamp team


## License

[MIT]()



📔 Contact me: 
📩 nataliaburrey@gmail.com
