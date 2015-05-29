# openwebif.py
Provides a python interface to interact with a device running OpenWebIf

# Installation
Download the code, and run
pip install -e .

# Usage

import openwebif.api

openweb_api = openwebif.api.Client('192.168.2.5')

is_in_standby = openweb_api.toggle_standby()
