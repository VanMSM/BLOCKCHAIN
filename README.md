# PYCHAIN, A BLOCKCHAIN BASED LEDGER

___

![BlockChain_Banner-2](https://user-images.githubusercontent.com/80144026/131240308-6e847480-ce37-43a3-9160-12a21e678f64.jpg)

This is a blockchain-based ledger system project, complete with a user-friendly web interface. This ledger should allow users to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.
__

## Project Images

###  Pychain Ledger run on Streamlit

<img width="1256" alt="Screen Shot 2021-08-28 at 10 54 08 PM" src="https://user-images.githubusercontent.com/80144026/131240283-58b0192c-f5ba-4942-87f1-a9e4e8dc38df.png">
![Unknown-1](https://user-images.githubusercontent.com/80144026/131240286-bf594a3e-812d-4488-8ebc-3b09a1cc2eac.jpeg)


### * After a block is added

<img width="970" alt="Screen Shot 2021-08-28 at 10 19 35 PM" src="https://user-images.githubusercontent.com/80144026/131239794-6c6103ea-2108-45c5-8b38-94780f45afc1.png">

### * Block Contents and Hashes

<img width="845" alt="Screen Shot 2021-08-28 at 10 08 08 PM" src="https://user-images.githubusercontent.com/80144026/131239799-4593ae45-2105-4c29-828d-23fad17627c8.png">

___


## Technologies

This project is written in Python within the Visual Code environment with the following packages:

* Pandas
* Streamlit
* Hashlib


## Installation Guide
Before running the application first install and verify the following dependencies:

* Pandas from PyPI
 ```python
 pip install pandas
 ```
 
* Steamlit from PyPI
 ```python
 pip install streamlit
 ```

Next, Import the Modules

 ```python
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
```
Clone to your local repo and open in VS Code


## How to Use

In the terminal, navigate to the project folder and run the Streamlit application by using "streamlit run pychainapp.py"
Enter values for the sender, receiver, and amount, and then click the "Add Block" button.
Verify the block contents and hashes in the Streamlit drop-down menu.


## License 
MIT



