# Crypto_Wallet
You work at a startup that is building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency. In this Challenge, you will complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.

## Technologies 

Streamlit 

Dotenv 

Dataclass 

Web3 - an Ethereum Javascript API 

os - miscellaneous operating system interfaces

Requests - HTTP library for python Pandas

BIP44 - Bitcoin improvement proposals 

## Instaltion

import streamlit as st

from dataclasses import dataclass

from typing import Any, List

from crypto_wallet import generate_account, get_balance, send_transaction

import os

import requests

from dotenv import load_dotenv

load_dotenv()

from bip44 import Wallet

from web3 import Account

from web3.auto.infura.kovan import w3

from web3 import middleware

from web3.gas_strategies.time_based import medium_gas_price_strategy

## Usage

After cloned the files in your personal computer you can lauch the fintech_finder.py with the streamlit and than follow the steps bellow:
- First you have to choose the developer and how many hours he/she gonna be paid.
- 
![Screen Shot 2021-05-16 at 9 12 55 PM](https://user-images.githubusercontent.com/75823252/118431634-a92dea00-b68b-11eb-9694-a4ce3f29785c.png)

- Than you gonna click to send transaction:
- 
![Screen Shot 2021-05-16 at 9 13 04 PM](https://user-images.githubusercontent.com/75823252/118431831-0e81db00-b68c-11eb-80a5-ae46f84ec820.png)

- After a few seconds you gonna see the confirmation for the transaction: 
- 
![Screen Shot 2021-05-16 at 9 15 16 PM](https://user-images.githubusercontent.com/75823252/118431884-28bbb900-b68c-11eb-935c-062038784014.png)

_ You also can check on https://kovan.etherscan.io/ inserting the transaction or id.

![Screen Shot 2021-05-16 at 9 22 38 PM](https://user-images.githubusercontent.com/75823252/118432235-ef377d80-b68c-11eb-8fb8-d664716d89b8.png)


## Contributors
Matheus Araujo

## License
Public



