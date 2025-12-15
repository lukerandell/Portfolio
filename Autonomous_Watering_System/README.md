This is the Automatic Watering System I created for my A-Level Computer Science project 

Components Used:
  - Raspberry Pi 4b
  - DHT11 Temperature and Humidity Sensor
  - DS18B20 Soil Temperature Sensor
  - Capacitive Soil Moisture Sensor
  - Light Dependant Resistor
  - Smaller Components: Resistors, Capacators, Jumper wires, Breadboard.

Aim of project:
This project was made for more accurate automatic watering systems than market available systems, and for environment monitoring. A locally hosted website allowed for viewing trends in tempeatures and humidity with future upgrading possible with barometric sensors, rain gauges etc.

The System Starts by first checking the LDR, preventing watering during bright sunshine.
Then, the soil moisture sensor is checked to prevent watering already wet soil.
Finally, the local forecast for the next 3 hours is checked for incoming rain.

Skills Developed:
1. Programming:
   - The main program was coded in Python on a Raspberry Pi.
   - A basic locally hosted website was coded in HTML.
   - A simple SQL database
   - API Requests
2. Basic Eletronics:
   - Wiring and Soldering
   - Components and datasheet lookups
   - Raspberry Pi GPIO

