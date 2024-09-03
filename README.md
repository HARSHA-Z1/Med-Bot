# Med-Bot
================

## Overview
------------

MedBot is a Python-based application designed to manage medicine inventory using barcode scanning, database management, and servo motor control with an Arduino. The system allows users to scan barcodes to add medicines to their cart, check for expired stock, and view existing stock. The project integrates several technologies to create a functional and automated medicine dispensing system.

## Features
------------

1. **Barcode Scanning**: Utilizes the device camera to scan and decode barcodes on medicine packages.
2. **Database Management**: Connects to a MySQL database to store and retrieve medicine information, including name, expiry date, price, quantity, and shelf location.
3. **Servo Motor Control**: Controls servo motors connected to an Arduino to automate the dispensing of medicines.
4. **Real-Time Inventory Management**: Updates inventory quantities based on user input and ensures expired stock is flagged.
5. **Checkout Slip**: Generates a detailed checkout slip displaying the purchased items.

## Hardware Requirements
------------------------

1. **Arduino Board**: An Arduino board to control the servo motors.
2. **Servo Motors**: Four servo motors to automate the dispensing mechanism.
3. **Camera**: A camera to scan medicine barcodes.
4. **Computer**: A computer with Python installed.

## Software Requirements
------------------------

1. **Python 3.x**: The programming language used for the application.
2. **MySQL**: The database management system used to store medicine information.
3. **Arduino IDE**: The integrated development environment used to program the Arduino board.

## Usage
-----

### Adding Medicines to Cart

1. Select option 1.
2. Scan the barcode of the medicine using the camera.
3. Enter the required quantity and confirm the purchase.
4. The Arduino-controlled servos will dispense the selected medicine.

### Checking Expired Stock

1. Select option 2.
2. The system will display all expired medicines in the database.

### Displaying Stock

1. Select option 3.
2. The current stock, including all medicine details, will be displayed.




