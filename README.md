# SafeNest: Home Security System with Arduino

## Overview

SafeNest is a cost-effective home security solution built around an Arduino platform. It utilizes a Passive Infrared (PIR) sensor to detect motion and activates a buzzer as an alert mechanism. For enhanced security, the system integrates a GSM module capable of sending SMS alerts to the homeowner, ensuring real-time monitoring and protection.

## Set-up

![Alt text](https://github.com/divyaprabha1805/SafeNest/blob/main/Image.png)

## Features

- **Motion Detection**: Utilizes a PIR sensor to detect unauthorized movement.
- **Audible Alert**: Triggers a buzzer to notify of detected motion.
- **SMS Notification**: Sends SMS alerts to the homeowner via a GSM module.
- **Real-Time Monitoring**: Provides immediate alerts for prompt action.
- **Cost-Effective**: Uses affordable components suitable for DIY enthusiasts.

## Hardware Components

- **Arduino Board**: Acts as the central controller.
- **PIR Sensor**: Detects motion within its range.
- **Buzzer**: Emits sound alerts upon motion detection.
- **GSM Module**: Facilitates SMS communication with the homeowner.

## Installation & Setup

1. **Connect the Components**:
   - Wire the PIR sensor to the designated input pins on the Arduino.
   - Connect the buzzer to an output pin.
   - Integrate the GSM module, ensuring proper connections for power and communication.

2. **Upload the Code**:
   - Download the Arduino IDE.
   - Open the provided code file.
   - Select the correct board and port.
   - Upload the code to the Arduino.

3. **Configure the GSM Module**:
   - Insert a SIM card with SMS capabilities.
   - Set up the recipient phone number in the code.

4. **Test the System**:
   - Activate the system and simulate motion to verify functionality.

## Usage

Once set up, the system continuously monitors for motion. Upon detecting movement, it triggers the buzzer and sends an SMS alert to the homeowner, providing immediate notification of potential security breaches.

