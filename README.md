# PY-ACR122U

<img src="http://downloads.acs.com.hk/product-website-image/acr38-image.jpg" width="150" height="150">

This is a python library for the ACR122u NFC reader

## Installation
- git clone https://github.com/Naexys/py-acr122u.git
- cd py-acr122u
- pip install requirements.txt

## Usage
```python
from src import nfc

reader = nfc.Reader()
reader.print_data(reader.get_uid())
reader.info()
```
- python main.py