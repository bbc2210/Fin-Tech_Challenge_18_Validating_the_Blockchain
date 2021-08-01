# Fin-Tech_Challenge_18_Validating_the_Blockchain

You’re a fintech engineer who’s working at one of the five largest banks in the world. You were recently promoted to act as the lead developer on their decentralized finance team. Your task is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.



## Overview

#### 1. The blockchain and its validity

See the validity result at the bottom of the picture.

When it comes to `proof of work`, notice how `difficulty` influences `nonce`. The higher the difficulty is set, the higher the nonce is. For example, with difficulty 2, the nonces, where the data index is ranging from 1 to 3, are approximately one hundred; likewise,  with difficulty 5, the nonces, where the data index is ranging from 4 to 5, are much higher than nonces with difficulty 2.

![ledger_validation.JPG](images/ledger_validation_all.JPG)



#### 2. The Difficulty setting

![difficulty_5.JPG](images\difficulty_5.JPG)



#### 3. The block inspector

![Block_Inspector_2.JPG](images\Block_Inspector_2.JPG)





## Technologies

This project leverages python 3.7 with the following packages:

* [Streamlit](https://discuss.streamlit.io/t/set-default-height-and-width-for-st-write-for-magic/729/2) - Streamlit is an open-source app framework for Machine Learning and Data Science teams. Create beautiful data apps in hours, not weeks. All in pure Python.



## Installation Guide

To install the Streamlit library, check that your `dev` virtual environment is active, and then run the following command:

```python
pip install streamlit
```



## Usage

To use the  application simply clone the repository, and run the **pychain.py** with:

```bash
streamlit run pychain.py
```

