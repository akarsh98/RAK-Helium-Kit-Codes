# # DIY-Helium-Node-Using-RAK-Helium-Developer-Kit

Video tutorial : [https://youtu.be/ULMnPckZp1M](https://www.youtube.com/watch?v=J2f_AVx-WsE&list=LL&index=3)

![alt text](https://github.com/akarsh98/RAK-Helium-Kit-Codes/blob/main/Helium%20Developer%20Kit/5.JPG)

Today we have with us the awesome RAK Helium Developer Kit based on Wisblock technology. The main advantage of this technology is that the boards are designed in such a manner that they does not to be soldered from one another. We can connect these with one another by attaching them using on board connectors. They are just like legos and connect with one another in just a snap. This makes these devices very easy to use and reliable as well. The Kit that we have with us has a lot of different sensors in it and some Wisblock IO core boards with other accesories such as antenna, screwdriver and micro USB cable.


![alt text](https://github.com/akarsh98/RAK-Helium-Kit-Codes/blob/main/Helium%20Developer%20Kit/1.JPG)

WisBlock is a modular system that makes it easy to implement a low power wide area network (LPWAN) into your IoT solution. WisBlock is going with your solution from rapid prototyping to mass production without the need to create new hardware modules for each step.In the development phase, WisBlock modularity allows you to test different microcontrollers, sensors, communication technology, IO options by changing modules with the simple plug-in modules.WisBlock industrial-grade modules can be used in mass production without the need to redesign the prototypes.Even once deployed, devices can be modified or repaired with minimal waste and effort. WisBlock is created with 4 modular blocks.

WisBlock Base is the baseboard that connects everything.
WisBlock Core is the computation and communication module.
WisBlock Sensor is a selection of sensor and input modules.
WisBlock IO extends the output and communication possibilities of the WisBlock Core.


![alt text](https://github.com/akarsh98/RAK-Helium-Kit-Codes/blob/main/Helium%20Developer%20Kit/13.JPG)

We will be using only the RAK4361 WIsblock core module for this project. We will attach a LoRa Antenna to this board and the program it in such a manner that it sends some small messages such as Hello World messages which are sent to the Helium Staging Console through a Gateway acting as a Data only Hotspot. The live data transfer can be seen using the visualizer on the Staging Console but as the messages are in encoded form, we need to decode them using base64 decoder to retrieve the original message. In the next project, we will expand our project a bit more by attaching an environment sensor to the IO board and storing the data in a Google Sheet. 



![alt text](https://github.com/akarsh98/MQTT-ESP8266-demo-with-Reyax/blob/main/Home%20Automation%20Board/jlcpcb.JPG)


You must check out [JLCPCB](https://jlcpcb.com/aka) for ordering PCBs online for cheap!

You get 10 good quality PCBs manufactured and shipped to your doorstep for 2$ and some shipping. You will also get a discount on shipping on your first order. To design your own PCB head over to easyEDA, once that is done upload your Gerber files onto [JLCPCB](https://jlcpcb.com/aka) to get them manufactured with good quality and quick turnaround time
