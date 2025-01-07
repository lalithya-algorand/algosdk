# Algorand Blockchain Project

This project demonstrates creating accounts, processing payments, and creating tokens on the Algorand blockchain using Python and the Algorand SDK.

## Prerequisites
- Python 3.x installed on your machine
- Algorand SDK (`py-algorand-sdk`) installed in a virtual environment
```bash
pip install py-algorand-sdk
```

## Setup Instructions

### 1. Create a Virtual Environment
Run the following command to create a virtual environment:
```bash
python -m venv venv
```

### 2. Activate the Virtual Environment
 #### On Windows:
```bash
venv\Scripts\activate
```
#### On macOS or Linux:
``` bash
source venv/bin/activate
```
### 3. Using Environment Variables
Store sensitive information like API keys in a .env file.
In your .env file, add the following variables:

 - **PRIVATE_KEY:** Your private key for the Algorand account.
- **ALGOD_TOKEN:** The token for authenticating requests to the Algorand API.
- **ALGOD_URL:** The URL of the Algorand Testnet API.
- **ALGOD_PORT:** The port for the Algorand API.

### 4. Running the Scripts
- **account.py:** Script to manage Algorand accounts
- **payment.py:** Script to process payments
- **token_create.py:** Script to create tokens

### 5. Running the Scripts

- **account.py**: Script to manage Algorand accounts
  ```bash
  python account.py
- **payment.py:** Script to process payments
  ```bash
  python payment.py
  ```
- **token_create.py:** Script to create tokens
  ```bash
  python token_create.py
  ```
