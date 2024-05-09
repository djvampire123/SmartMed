# SmartMed: Automated IoT-Enabled Medicine Environment

SmartMed is an innovative project designed to automate the management and dispensing of medications using Internet of Things (IoT) technologies. It leverages a Raspberry Pi to control hardware components that dispense medications at scheduled times and confirms administration via a user-friendly web interface.

## Features

- **Automated Medicine Dispensing:** Utilizes Raspberry Pi to control dispensing mechanisms ensuring medications are provided at the correct times.
- **Web Interface:** Provides a user interface for setting up medication schedules and monitoring dispensing activities.
- **Notification System:** Sends out alerts and notifications to users regarding medication schedules and other important information.

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine or Raspberry Pi for development and testing purposes.

### Prerequisites

You will need the following tools and components to set up and run this project:

- Raspberry Pi (any model that supports GPIO pins)
- Python 2.7 or higher
- Tornado Web Server
- Motor (for MongoDB interactions)
- GPIO hardware setup for dispensing mechanism

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/smartmed.git
   cd smartmed
2. **Install the required Python packages:**
    ```bash
    pip install -r requirements.txt

3. **Hardware Setup:**
Connect your GPIO components according to the schematics provided in the hardware directory.

4. **Configure the software:**
Modify the configuration files in the config directory to match your hardware setup and network configuration.

5. **Run the application:**
    ```bash
    python server.py
### Usage
After setting up the SmartMed system, navigate to the web interface by accessing the Raspberry Pi's IP address on your network:

   ```arduino
    http://<raspberry-pi-ip>:5000/
```
From here, you can set up medication schedules, monitor dispensing activities, and manage user settings.

**Built With**

Tornado - Asynchronous web server and web application framework.

MongoDB - NoSQL database used for storing application data.

Python - Main programming language used.

Raspberry Pi - Used as the main hardware controller for the dispensing mechanism.

**License**

This project is licensed under the MIT License - see the LICENSE.md file for details
