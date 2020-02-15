# Arduino-Python-Comm
Serial port comminication between Arduino and Python Script

This example was created to change servo motor angle.

Load Arduino code. Than start python script with

> python3 main.py

You should check your port path. 
In the servo.py, you should configure this lines.
> self.port_path = "/dev/ttyACM0"
> self.boutrate = 9600
