# IOT-based-Home-automation-using-a-web-page
In this home automation project, you can control up to eight home appliances using both physical switches and a web-based interface accessed through your local Wi-Fi network. The project uses a NodeMCU development board, which is based on the ESP8266 Wi-Fi chip, and a collection of relays to control the appliances.

Here's an overview of the project:
**Hardware Setup**:
Connect the NodeMCU board to a breadboard and provide power (3.3V) and ground connections.
Connect up to eight relay modules to the NodeMCU board, with each relay controlling a different home appliance. Make sure to connect the relay modules safely and according to electrical safety regulations.
**Web Page Code:**
Create a web page with eight switches (HTML input type="checkbox"), each representing one of the appliances.
Use JavaScript to communicate with the NodeMCU board over Wi-Fi using the ESP8266's built-in web server.
**NodeMCU Code:**
Write code for the NodeMCU using the Arduino IDE, which includes:
Setting up a web server to host the web page and handle commands from it.
Reading the state of the switches on the web page and controlling the relays accordingly.
**Getting the NodeMCU's IP Address:**
After uploading the code to the NodeMCU, open the Serial Monitor in the Arduino IDE. The IP address of the NodeMCU will be displayed.
**Accessing the Web Page:**
Open a web browser on your laptop or mobile device, and enter the NodeMCU's IP address in the address bar.
The web page with eight switches will be displayed.
**Testing:**
After connecting all the devices to the same Wi-Fi network, you should be able to control each of the appliances using both the physical switches and the switches on the web page.


This project demonstrates how you can use the ESP8266's web server capabilities to create a simple, cost-effective home automation system that can be controlled from a web browser or a mobile device with a browser.
