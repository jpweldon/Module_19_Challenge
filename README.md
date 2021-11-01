# Module_19_Challenge

# Fintech Finder

---

## Introduction:

The premise of this project is that I work at a startup that is building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, I have been tasked with integrating the Ethereum blockchain network into the application in order to enable my customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

I will complete the code that enables my customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, I will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work.

---

## Technologies

This project leverages python 3.7 with the following modules:

* [streamlit](https://streamlit.io) - For turning data scripts into shareable web apps.

* [dataclasses](https://docs.python.org/3/library/dataclasses.html) - Provides a decorator and functions for automatically adding generated special methods.

* [typing](https://docs.python.org/3/library/typing.html) - Provides runtime support for type hints.

* [os](https://docs.python.org/3/library/os.html) - Provides a portable way of using operating system dependent functionality.

* [requests](https://docs.python-requests.org/en/master/) - A HTTP library for Python.

* [dotenv](https://pypi.org/project/python-dotenv/) - For reading key-value pairs from a .env file and setting them as environment variables.

* [bip44](https://pypi.org/project/bip44/) - A Python implementation for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard.

* [web3](https://web3py.readthedocs.io/en/stable/overview.html) - A Python library for connecting to and performing operations on Ethereum-based blockchains.

* [matplotlib](https://matplotlib.org/stable/users/index.html) - For embedding plots in the application.

---

## Installation Guide

Before running the application first install the following dependencies:

```python
  pip install streamlit
  python -m pip install requests
  pip install python-dotenv
  pip install bip44
  pip install web3==5.17
  pip install mkdocs
```

---

## Usage

To use the Fintech Finder application:

Clone the Module_19_Challenge repository from GitHub:

'git clone https://github.com/jpweldon/Module_19_Challenge.git'

Review the crypto_wallet.py and fintech_finder.py programs.

Run the Fintech Finder app in the terminal by using:

'streamlit run fintech_finder.py'

Review the Screen Captures from Etherscan of customer address balance and history, transaction details, and recipient address balance and history, following a successful run of the program. The screen captures are included in this repository.

---

## Contributors

John P Weldon

Email: johnpweldon01@gmail.com

[LinkedIn:] (www.linkedin.com/in/john-weldon-333b0695)

---

## License

MIT

---