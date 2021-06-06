# lnbitsbot

A starter template for running bots based off of lnbits.com or your own install.

Basic outline with lnbits as the backend for a python TG bot:

- create a wallet on lnbits tied to a TG username
- TG users can send links to nonTG users
- link user to lnbits web interface so they can use and add features
- send/receive/tips to other TG users
- gift sats with custom image and message. unclaimed sats should expire and return to sender
- instructions with easy on ramp for users who don't hold sats or bitcoin
- /tx, /log, /lnurl commands
- Add throttle tx size based on node capacity

Getting Started

```
git clone https://github.com/lightningames/lnbitsbot
cd lnbitsbot
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
pip install -e .
```

Check linting and formatting
`pre-commit run -a`

Run Tests

```
TBD
TBD
```
