# HOME-AUTOMATION-WITH-BLUETOOTH

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: PIYUSH THAKUR

*INTERN ID*: CT04WK180

*DOMAIN*: EMBEDDED SYSTEM 

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

# PROJECT TITLE:- HOME AUTOMATION WITH BLUETOOTH

# PROBLEM STATEMENT OF PROJECT:
DESIGN A BLUETOOTH-CONTROLLED HOME AUTOMATION SYSTEM TO SWITCH DEVICES ON AND OFF.

# COMPONENTS REQUIRED:
Arduino Uno/Nano Bluetooth Module (e.g., HC-05 or HC-06) 4-Channel Relay Module Smartphone with a Bluetooth terminal app Electrical appliances (e.g., LED, fan) Breadboard and jumper wires.

# CONNECTIONS
1) Bluetooth Module (HC-05):
VCC → 5V (Arduino) 
GND → GND (Arduino) 
TX → RX (Arduino) 
RX → TX (Arduino)

2) Relay Module:
IN1 → Pin 8 (Arduino) 
IN2 → Pin 9 (Arduino) 
IN3 → Pin 10 (Arduino) 
IN4 → Pin 11 (Arduino) 
VCC → 5V (Arduino)
GND → GND (Arduino)

# POWER SUPPLY:
Ensure the relays can handle the voltage and current of connected devices. For safety, use a separate power supply for high-voltage appliances.

# APPLIANCES:
Connect each appliance's positive terminal to a relay's NO (Normally Open) terminal. Connect the common (COM) terminal of each relay to the power source.

# WORKING:
Pair the HC-05 module with your smartphone. Use the default PIN (1234 or 0000). Open a Bluetooth terminal app. Send the following commands to control devices: 1: Turn ON Device 1 2: Turn OFF Device 1 3: Turn ON Device 2 4: Turn OFF Device 2 5-8: Control Device 3 and Device 4 similarly

# USE CASES OF THIS PROJECT
1) Controlling Lights and Appliances
2) Smartphone as a Remote Controller
3) Accessibility for Elderly or Disabled Users
4) Fan Speed or Light Dimming Control
5) Manual Override and Auto Mode


# CIRCUIT DIAGRAM 

![Image](https://github.com/user-attachments/assets/390517c8-bd15-4865-ac23-8eda1436bb9f)
