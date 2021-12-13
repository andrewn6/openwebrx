Porting OpenWebRTX to Python3.

I did this because the project got discontinued, and it requires Python 2 which is old and does not get any security patches since its deprecated as of January 2020.

All code in this repo released under its respective license.

*I do not own this code, it is just a fork of it for it to support Python 3 and improve it.*


How do I run this?

`git clone https://github.com/anddddrew/openwebrx`

`cd openwebrx/`

`python3 openwebrx.py`

Then go to http://localhost:8073.

*NOTE*

Make sure to install csdr or else you cannot run OpenWEBRX

You can do so by cloning this repo:
https://github.com/ha7ilm/csdr

`cd csdr/`

`make`

`sudo make install`

After that you should be good to go :)
