# Rubber Ducky with Arduino

This repo contains the code for the rubber ducky with arduino. This code works with Arduino Micro, Leonardo and Pro Micro. It opens CMD 
then downloads `https://github.com/Abtaha/Remote-Command-Execution-For-Hacking/blob/master/client.py` to a `window` folder in the C: 
drive. This way the victim would not suspect it. Meanwhile the attacker runs `https://github.com/Abtaha/Remote-Command-Execution-For-Hacking/blob/master/server.py`
on their own PC. After downloading the client file, the ducky runs it which gives us access to the victim's computer.

## Demo

![Demo](https://github.com/Abtaha/Rubber-Ducky-with-Arduino/blob/master/Demo.png)
