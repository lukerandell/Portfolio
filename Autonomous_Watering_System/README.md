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

Challenges Ovecome
Getting water into the raised bed from the pump came in the form of a hosepipe along the side of the bed with holes drilled in at regular lengths.
I designed and 3D printed some clips to hold the hosepipe along the edge, however out of PLA. Just a week in the sun and I learned why this material wasn't optimal. These were then reprinted in white PETG and held up well, as with the 3D printed Stevenson Screen temperature and humidity sensor holder.
