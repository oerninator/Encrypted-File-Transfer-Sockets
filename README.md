
# Encrypted File Transfer

This project demonstrates a simple encrypted file transfer between a client (sender) and a server (receiver) using Python's `socket` library for networking and `pycryptodome` library for encryption.

## Prerequisites

- Python 3.8 or higher
- Required library: `pycryptodome`

## Installation

To install the required library, run the following command:

```bash
pip install pycryptodome tqdm
```

## Usage

1. **Start the Receiver:**
   
   Run the `receiver.py` script to start the server that will receive and decrypt the file.

   ```bash
   python receiver.py
   ```

2. **Send a File:**
   
   Run the `sender.py` script to send an encrypted file to the server.

   ```bash
   python sender.py
   ```

   Ensure that the file you want to send is named `file` and is in the same directory as the `sender.py` script.

## Source

This project is based on a tutorial from YouTube: [Python Encrypted File Transfer](https://www.youtube.com/watch?v=wJanjCfyhAk)

Feel free to modify the scripts to fit your needs.
