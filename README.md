# LMS-nosql

## Introduction
LMS-nosql is a database-free version of a Library Management System (LMS). It writes data directly onto RFID cards, eliminating the need for a traditional database. The system supports reading and writing RFID card data and includes a keystroke function to type RFID data into any application.

## Functionalities
- **RFID Read/Write**: Read and write data directly from/to RFID cards.
- **Keystroke Function**: Automatically type RFID data into any application.
- **Web Interface**: User-friendly web interface for managing RFID operations.

## Installation

1. **Install Drivers**:
   - Navigate to the `dependencies` folder.
   - Extract `CDM-v2.12.36.4-WHQL-Certified.zip` and navigate to `CDM-v2.12.36.4-WHQL-Certified.zip` folder.
   - Install both drivers available in the folder.

2. **Install Python**:
   - Download and install Python from [python.org](https://www.python.org/downloads/).
   - Alternatively, install python from the installation file in the `dependencies` folder.

3. **Install Requirements**:
   - Open a terminal or command prompt.
   - Navigate to the project directory.
   - Run the following command to install required Python packages:
     ```bash
     pip install -r requirements.txt
     ```

4. **Start the Server**:
   - Double-click `server.py` or run it from the terminal:
     ```bash
     python server.py
     ```
   - Copy the link provided by the terminal and paste it into your web browser to access the application.

## Possible Bugs
- Ensure the correct COM port is selected, the buttons are active only when the port is selected.
- Verify that the RFID reader is properly connected.
- Check the terminal for any error messages.
- Before clicking `write data` button, make sure you place the card on top of the reader.
- Make sure a beep is heard on clicking write, if no beep is heard, take the card off from the reader, place it back on the reader and click the button again.
- Any hardware errors will result in wrong data while reading, just make sure that you tap the card again if any problems occur.

## Support
For support, please contact the maintainer at: [Joe Sanjo](mailto:joesanjo10@gmail.com)