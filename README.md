# ESP32-HTTP-Request-Project

# Task 3: HTTP Request in ESP32 Code to Retrieve Data from Database

## Description
This project demonstrates how to use an ESP32 to retrieve data from a database via HTTP requests. Depending on the data received, the ESP32 controls two LEDs (green and red) to signal whether a specific command is present or not. The simulation is conducted using [Wokwi](https://wokwi.com/), an online platform for IoT project simulations.


### Components Used
* ESP32 
* Green LED
* Red LED
* jumper wires

### Steps
1. Go to [Wokwi](https://wokwi.com/).

2. Create a new project and set up the ESP32 with the green and red LEDs.

3. Use the following code in your Wokwi project: https://github.com/GDHadeel/ESP32-HTTP-Request-Project/blob/main/sketch.ino

### Upload the Code to the ESP32

* Click on the "Start Simulation" button in Wokwi.

### Monitor the Serial Output

* Use the Serial Monitor in Wokwi to see the output.

### Host Your PHP File
* Ensure your PHP backend is hosted and accessible via a URL. The provided code uses the URL https://64f2844d-d3fd-455b-a192-2ca85e7199ec-00-2oovwbfrq1lzh.sisko.replit.dev/

* Replace the URL in the code with your hosted PHP file URL.


### Result / Output

* If there is no command recorded, the red LED will light up.
![image](https://github.com/user-attachments/assets/795f407d-fb1f-4bb7-a489-0a622a6f88de)

* If a command is present, the green LED will light up.
![image](https://github.com/user-attachments/assets/229d0096-ac6d-49be-a7da-b8c44a451121)


## Acknowledgements

https://wokwi.com/projects/393020133767191553

https://www.youtube.com/watch?v=9Vw5Y8SRi74




