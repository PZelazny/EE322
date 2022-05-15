# Lab 5

```ssh
$ sudo apt update
$ sudo apt install mosquitto mosquitto-clients
$ mosquitto_sub -h localhost -v -t "\$SYS/#"
```
![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%205/Pictures/LAB5_A.png)


```ssh
$ service mosquitto status
$ netstat -tln
```
![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%205/Pictures/LAB5_B.png)



```sh
$ mosquitto_sub -h localhost -v -t test/topic &
```sh
$ mosquitto_pub -h localhost -t test/topic -m "Hello"
```
![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%205/Pictures/LAB5_C.png)



```sh
$ sudo pip3 install -U paho-mqtt
$ git clone https://github.com/eclipse/paho.mqtt.python.git
$ cd ~/iot/lesson5
$ python3 client.py
```
![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%205/Pictures/LAB5_D.png)


Terminal 1 
```sh
$ python3 sub.py
$ python3 sub-multiple.py
$ python3 subcpu.py
```
Terminal 2
```sh
$ python3 pub.py
$ python3 pub-multiple.py
$ python3 pubcpu.py
```
![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%205/Pictures/LAB5_E.png)
