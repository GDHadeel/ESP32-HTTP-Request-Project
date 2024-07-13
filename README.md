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

3. Use the following code in your Wokwi project:

### sage

1. Open the esp32-http-request-project.ino file in Wokwi.

2. Configure your WiFi credentials:
     ```
     const char* ssid = "Wokwi-GUEST";
     const char* pass = "";
     ```

### Upload the Code to the ESP32

1. Click on the "Start Simulation" button in Wokwi.

### Monitor the Serial Output

1. Use the Serial Monitor in Wokwi to see the output.

### Host Your PHP File
1. Ensure your PHP backend is hosted and accessible via a URL. The provided code uses the URL https://64f2844d-d3fd-455b-a192-2ca85e7199ec-00-2oovwbfrq1lzh.sisko.replit.

2. Replace the URL in the code with your hosted PHP file URL.


## Acknowledgements






1. **Database Setup:**

   - Create a MySQL database named `robot`:
     ```
     const char* ssid = "Wokwi-GUEST";
     const char* pass = "";
     ```


