Simple script to periodically check course seats. Optionally notify by SMS when a seat is available.

OSX install:
```
sudo easy_install pip
sudo pip install requests[security] --ignore-installed six
sudo pip install beautifulsoup4
sudo pip install twilio
```

Help:
```
python ubc-cc.py -h
```