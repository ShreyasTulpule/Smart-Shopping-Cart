# Smart-Shopping-Cart

## Description:
Developed an IoT-based system to automate item tracking and billing in retail, aiming to streamline the shopping experience and enhance customer satisfaction.

## Technology used: 
IoT, NodeMCU, RFID, Web Development.

## Libraries Used:

- **ESP8266WiFi.h**: To connect to Wi-Fi.
- **WiFiClient.h**: Provides the ability to make network connections.
- **ESP8266WebServer.h**: Sets up a web server.
- **LiquidCrystal_I2C.h**: Controls the I2C LCD display.
- **Wire.h**: Used for I2C communication.
- **SPI.h**: Used for SPI communication, necessary for the RFID reader.
- **MFRC522.h**: Controls the RFID reader.

## Functionality:

- **Initialization**: Sets up Wi-Fi, LCD, and RFID.
- **Card Detection**: Detects when a new RFID card is presented.
- **Item Management**: Adds or removes items based on RFID tag and button state.
- **Display**: Shows information on the LCD and web server.
- **Network**: Serves a web page with current cart status.

## Outcome:
Successfully created a functional prototype that improves shopping efficiency, with a project cost of Rs. 735. Demonstrated the practical application of IoT in retail, offering a potential boost to customer experience.

## Project Team:
Shreyas Tulpule, Kashyap Talati, Devesh Sharma
