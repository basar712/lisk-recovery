# Lisk Passphrase Recovery Tool
A tool to recover a single missing word in a Lisk wallet passphrase.

![Demo](https://i.imgur.com/9Cp8cGL.gif)

## How it works
This tool currently can recover a passphrase if you know 11 of the 12 words. Enter 11 words and it will generate all possible combinations from the BIP 39 word list. These combinations will then open Lisk accounts via the API and check the account balance. If the balance is more than 0 the account passphrase will be found.

## Prerequisites
[git](https://git-scm.com/downloads)

[python](https://www.python.org/downloads/)

## Installation
``git clone https://github.com/lukeliasi/lisk-recovery.git``

``cd lisk-recovery``

``pip install -r requirements.txt``

## Run
You should run this tool in Terminal on OSX or cmd.exe or equivalent in Windows. Then when inside the project folder run:

``python recover.py``

## Test
Append `test` to the command to run test net mode. `python recovery.py test`. You can use this passphrase with a testnet balance to test: `day start afford analyst vibrant foot tiny curtain tennis pear taxi cause`

## Road Map
- Enable tool to be able to recover second passphrases.

### Help?
Need help setting up the tool? Email me via lukeliasi@gmail.com and I will reply as soon as possible.

### Donations
If this tool worked and recovered overwise lost funds consider donating: **10553198736677725420L**