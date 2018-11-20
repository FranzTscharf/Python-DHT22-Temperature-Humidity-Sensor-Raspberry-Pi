# Python-DHT22-Temperature-Humidity-Sensor-Raspberry-Pi
Python script for the DHT22 Sensor on the Raspberry Pi
## 1. Connecting Schema

![image1](https://tutorials-raspberrypi.de/wp-content/uploads/luftfeuchtigkeit_DHT11_Steckplatine-600x476.png)
![Image of Yaktoc2at](https://www.raspberrypi-spy.co.uk/wp-content/uploads/2012/06/Raspberry-Pi-GPIO-Layout-Model-B-Plus-rotated-2700x900.png)

## 2. Install the Dependencies
*update raspbian
```
sudo apt-get update
```
*install packages
```
sudo apt-get install build-essential python-dev python-openssl git
```
*load sensor library from Adafruit
```
git clone https://github.com/adafruit/Adafruit_Python_DHT.git && cd Adafruit_Python_DHT
```
*install it
```
sudo python setup.py install
```
## 3. First Measurements
*try reading the temperature and humidity using the example file
```
cd exmaples
sudo ./AdafruitDHT.py 22 4
```
