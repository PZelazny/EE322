# Lab 7

```ssh
$ sudo pip3 install -U psutil
$ cd ~/demo
$ cp ~/iot/lesson7/thingspeak_cpu_loop.py .
$ cp ~/iot/lesson7/thingspeak_feed.py .
$ cat thingspeak_cpu_loop.py
$ cat thingspeak_feed.py
$ python3 thingspeak_feed.py
```
![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%207/Pictures/LAB7_A.png)
![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%207/Pictures/LAB7_B.png)
![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%207/Pictures/LAB7_C.png)


![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%207/Pictures/LAB7_loop.png)



```ssh
$ sudo pip3 install -U gspread oauth2client
$ cd demo
$ cp ~/iot/lesson3/system_info.py .
$ cp ~/iot/lesson7/rpi_spreadsheet.py .
$ scp rpidata-*.json pi@192.168.x.xxx:/home/pi/demo
$ nano rpi_spreadsheet.py
$ python3 rpi_spreadsheet.py
```
![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%207/Pictures/LAB7_D.png)
![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%207/Pictures/LAB7_E.png)



![This is an image](https://github.com/PZelazny/EE322/blob/main/Lab%207/Pictures/LAB7_sheets.png)
