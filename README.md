# IoT-Based-Water-Level-Control-Monitoring-with-ESP8266
Leveraging IoT technology enables real-time water level monitoring and remote operational control, allowing users to visualize water levels and manage operations efficiently.


**Components**	<br>
1	NodeMCU ESP8266 WiFi Module	 <br>
2	JSN-SR04T Ultrasonic Sensor <br>
3	0.96" I2C OLED Display	 <br>
4	Hi-Link 220V AC to 5V DC Converter	 <br>
5	5V Relay Module	 <br>
6	Push Button Switch	<br>
7	AC Water Pump	 <br>
8	Pipes 2 meter or more	 <br>
9	Zero PCB Board	<br>

Circuit Diagram and Connections
![image](https://github.com/abhishektirkey/IoT-Based-Water-Level-Control-Monitoring-with-ESP8266/assets/93339541/90799b0e-d7b4-478f-9b53-9149f534059d)


The main controller used in this project is NodeMCU ESP8266 WiFi Module. For detecting the Water level of the tank, we can use Ultrasonic Sensor HC-SR04. But in this case, JSN-SR04T Waterproof Ultrasonic Sensor is a better choice. <br><br>
The JSN-SR04T is an ultrasonic distance sensor which is a waterproof version of the popular HC-SR04 sensor. It is designed to work in harsher environmental conditions where water or moisture might be present. The module uses ultrasonic sound waves to determine the distance to an object by emitting a sound wave, and then measuring the time it takes for the echo to return.
For displaying Water level, we can use 0.96″ SSD1306 OLED Display. The SSD1306 0.96″ OLED Display is a popular and compact display module used in many DIY electronics projects. It is based on the SSD1306 driver chip, which is designed to drive monochrome OLED screens. <br><br>
The display has a resolution of 128×64 pixels and provides a crisp, high-contrast image, making it suitable for various applications, such as displaying text, graphics, and icons. The module typically communicates with microcontrollers like Arduino, ESP8266, or Raspberry Pi using the I2C (Inter-Integrated Circuit) protocol. <br><br>
For supplying power and controlling the relay, we used HLK-PM01 AC to 5V DC converter Module. The Hi-Link AC to 5V DC converter is a compact and efficient power supply module that converts AC mains voltage (typically 90V-264V AC) to a stable 5V DC output. <br><br>
These modules are widely used in various electronics and IoT projects that require a 5V DC supply from the main power. <br><br>
