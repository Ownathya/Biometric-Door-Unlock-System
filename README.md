# Biometric-Door-Unlock-System

Descrtion :    
A biometric door unlock system is an advanced security solution that uses unique biological characteristics, such as fingerprints, facial recognition, or retinal scans, to access authorized individuals. The system quickly scans and matches the user's biometric data with stored profiles, unlocking the door only if a match is found.


Components Required :    

Arduino (e.g., Arduino Uno)    
Adafruit Fingerprint Sensor: Captures and verifies fingerprints.    
Relay Module: Controls the locking mechanism of the door.    
Connecting Wires: To connect the components together.    
Solenoid Lock: Its Locks the door and Open the door.


How It Works

Fingerprint Sensor Initialization: The system initializes the fingerprint sensor and verifies the connection. If the sensor is not properly connected or initialized, the program halts to prevent further operation.

Fingerprint Detection: In the main loop, the system continuously scans for fingerprints. If a fingerprint is detected and matches a stored template, the system proceeds to unlock the door.

Relay Activation: When a valid fingerprint is found, the relay is activated, which unlocks the door. The relay remains activated for a specified delay (3 seconds in this case) before it deactivates, locking the door again.

Security and Efficiency: The system adds a small delay between scans to ensure efficient operation and prevent unnecessary resource usage.


Usage

Clone the repository and upload the code to your Arduino.    
Connect the fingerprint sensor, relay module, and other components according to the pin definitions in the code.    
Power the system, and it will automatically begin scanning for fingerprints.    

This system is ideal for enhancing the security of any access point, such as doors, safes, or any other entry points where biometric verification is desired. The use of fingerprint recognition adds an extra layer of security, ensuring that only authorized individuals can unlock the door.

Feel free to contribute to this project by adding new features, improving efficiency, or expanding its capabilities!
