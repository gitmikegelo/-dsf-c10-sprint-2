## Additional instructions for installing `keyring` for Mac and Linux


### Linux (Standalone/VM/WSL )

Do the following on the terminal

sudo apt install build-essential libpython3-dev libdbus-1-dev
pip install dbus-python

### Mac

`keyring` will use Mac's `Keychain` app to store the passwords. If its your first time running the code, a popup should appear when running the keyring cell. Please make sure you grant permissions to python/browser