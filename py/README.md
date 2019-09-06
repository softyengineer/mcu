Digital Bitbox Python
============

Python (v2 or v3) code supporting the [Digital Bitbox](https://digitalbitbox.com) hardware wallet.

### Developer interface

Use `send_command.py` and `dbb_utils.py` to communicate with a Digital Bitbox. See the [API](https://shiftcrypto.ch/bitbox01/api/5.0.0/) for available commands.

Dependencies:

- [Python](http://python.org)

The code uses the following additional Python libraries: `os`, `sys`, `struct`, `json`, `base64`, `pyaes`, `hashlib`, and `hidapi`.
