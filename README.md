# Visitors-entry-scanner-IOT
To design and implement a visitor’s entry scanner in commercial areas.

The Visitors Scanner is the device that scans the person who is entering the private or public area just before the entry of the area along with the regular scanning process by security. The device can scan the temperature, heartbeat and alcoholic content of the person. If the person is having the described symptoms as mentioned, they should not be allowed to enter the area. By using this device we can give utmost security to the visitor. 

# Design

https://github.com/Spurthisk/Visitors-entry-scanner-IOT-/blob/master/IOT%20DESIGN%20FINAL.PNG

The main purpose of the proposed system is to build the visitors scanning device that scans the person who is entering the private or public area just before the entry of the area along with the regular scanning process by security. The device can scan the temperature, heartbeat and alcoholic content of the person. 
 
Input is given in the form of a person's body temperature, pulse rate and the alcohol content in the system. Body temperature is measured with the MLX90614 sensor , Pulse rate through Heart rate pulse sensor and alcohol detection through MQ-3 sensor. All these inputs are monitored through the main board i.e Arduino uno board. and then these data is analysed and compared with the threshold and then it displays the output. Later these data is managed with the ESP8266-01 wifi module with the Thingspeak in the cloud. 
 
 
