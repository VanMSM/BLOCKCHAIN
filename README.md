# PYCHAIN, A BLOCKCHAIN BASED LEDGER



![Unknown](https://user-images.githubusercontent.com/80144026/129490446-1aca9208-eaef-48e9-9fdf-d9780fe8eb83.jpeg)


This is a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow users to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

<img width="1710" alt="Screen Shot 2021-08-15 at 12 21 25 PM" src="https://user-images.githubusercontent.com/80144026/129490158-ac9458aa-5eb7-4c71-8c44-ccc616603341.png">


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



