📡 Bluetooth Jammer with ESP32 & NRF24L01+ 🚀

Overview 🌐
This project demonstrates how to configure an ESP32 microcontroller to transmit continuous signals across various channels in the 2.4 GHz frequency band using the NRF24L01+ module. This setup can interfere with Bluetooth communications within its range. Note: Deploying jammers in real-world environments is illegal in many countries, including the United States, due to their potential to disrupt legitimate communications. Always ensure compliance with local laws and regulations before engaging in such activities.

Hardware Requirements 🛠️

•	ESP32 Development Board: A microcontroller with Wi-Fi and Bluetooth capabilities.
•	NRF24L01+ Module: A 2.4 GHz transceiver module for RF communication.
•	Push Button: For toggling between different jamming modes.
•	Connecting Wires: For establishing connections between components.


Connections 🔌

NRF24L01+ Pin	      ESP32 Pin
GND	                  GND
VCC	                  3.3V
CE	                  GPIO16
CSN	                  GPIO15
SCK                  	GPIO14
MOSI	                  GPIO13
MISO                  	GPIO12


 
Software Requirements 💻
•	Arduino IDE: For programming the ESP32.
•	RF24 Library: For interfacing with the NRF24L01+ module.
•	ezButton Library: For handling button inputs.

Setup Instructions 📝
1.	Install Arduino IDE: Download and install the Arduino IDE from the official website.
2.	Configure ESP32 in Arduino IDE:
o	Add the ESP32 board manager URL in the Arduino IDE preferences.
o	Install the ESP32 board package via the Board Manager.
3.	Install Required Libraries:
o	Use the Library Manager in Arduino IDE to install the RF24 and ezButton libraries.
4.	Upload the Code:
o	Select the appropriate ESP32 board and port.
o	Upload the provided code to the ESP32.


Code Explanation 🧑‍💻
The provided code initializes the NRF24L01+ module and sets up SPI communication. It configures the module to transmit continuous signals across various channels in the 2.4 GHz band. The push button allows toggling between different jamming modes.
Important Considerations ⚠️
•	Legal Compliance: Ensure that the use of such a device complies with local laws and regulations. Unauthorized jamming is illegal in many jurisdictions.
•	Power Supply: The NRF24L01+ module requires a stable 3.3V power supply. Consider using a capacitor to stabilize the voltage.
•	Testing Environment: Conduct testing in a controlled environment to prevent unintended interference with other devices.
•	ESP32 and NRF24L01+ Tutorial: A tutorial on connecting ESP32 with NRF24L01+.


Disclaimer ⚖️
This project is intended solely for educational purposes. The creator does not endorse or encourage the use of jammers in unauthorized or illegal activities. Always ensure compliance with local laws and regulations before engaging in such projects.

