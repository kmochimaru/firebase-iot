# FirebaseIOT

Requirments
- python3
- pyrebase
- Adafruit_DHT
- Adafruit_MCP3008 (Hardware) 

References
- https://github.com/thisbejim/Pyrebase
- https://learn.adafruit.com/dht-humidity-sensing-on-raspberry-pi-with-gdocs-logging/software-install-updated
- https://learn.adafruit.com/raspberry-pi-analog-to-digital-converters/mcp3008
- https://www.electronicshub.org/controlling-a-dc-motor-with-raspberry-pi/

* install package use pip3 and runscript use python3 file.py
* check package install command "pip3 list"

How to set default python3
- sudo nano ~/.bash_aliases then add alias python=python3
- source ~/.bash_aliases
- python --version
How to set startup python script
- sudo nano /etc/rc.local
- add script before exit su pi -c "python3 FirebaseIOT/FirebaseIOT.py"
- sudo nano /etc/profile
- add script below sudo /etc/rc.local

