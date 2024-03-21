                                                     KIT-KALAIGNARKARUNANIDHI INSTITUTE OF TECHNOLOGY
                                                            (AN AUTONOMOUS INSTITUTION)
                                                           COIMBATORE, TAMIL NADU-641402
                                                      Affiliated to Anna University, Chennai
                                      Accredited by NAAC with ‘A’ Grade | Accredited by NBA (CSE, ECE, EEE & MECH)


                                                         SMART HOME AUTOMATION DEVICES
 
                                                                  ABSTRACT



Home automation is the automatic control of household electronic devices and appliances. It can be used to make homes more comfortable, efficient, and secure. WiFi-based home automation systems use WiFi modules to connect to the internet and allow users to control their devices remotely. It allows users to create custom schedules for devices, turn devices on or off, and change other settings to fit their preferences. WiFi-based home automation systems use WiFi to connect devices to the internet, allowing them to be controlled remotely. The ESP8266 is a low-cost, low-power WiFi module that is ideal for home automation applications. It is easy to program and has a wide range of features, including built-in timers, sensors, and actuators.

This paper presents a home automation system that uses the ESP8266 to control a variety of devices, including lights, fans, and thermostats. The system can be controlled using a mobile app, a web interface, or voice commands. The system is designed to be easy to use and install. It can be used to save energy, improve security, and make life more convenient.
 
                                                                **INTRODUCTION**

The project aims to design an advanced home automation system using a normal web server and Wi-Fi technology. The devices can be switched ON/OFF and sensors can be read using a Personal Computer (PC) through Wi-Fi. Automation is the most frequently spelled term in the field of electronics. The hunger for automation brought many revolutions in the existing technologies. These had greater importance than any other technologies due to their user-friendly nature. These can be used as a replacement for the existing switches in a home which produce sparks and also result in fire accidents in a few situations. Considering the advantages of Wi-Fi an advanced automation system was developed to control the appliances in the house.

Wi-Fi (Short for Wireless Fidelity) is a wireless technology that uses radio frequency to transmit data through the air. Wi-Fi has initial speeds of 1mbps to 2mbps. Wi-Fi transmits data in the frequency band of 2.4 GHz. It implements the concept of frequency division multiplexing technology. The range of Wi-Fi technology is 40-300 feet. The controlling device for the automation in the project is an ESP8266 module. The data sent from the PC over Wi-Fi will be received by the Wi-Fi module connected to ESP8266. It reads the data and decides the switching action of electrical devices connected to it through Relays. works with flexibility in real-world applications on computer systems without the use of a GPU (graphics processing unit).
 

                                                               ** ESP8266 WIFI MODULE**




Description: The ESP8266 WiFi Module is a self-contained SOC with an integrated TCP/IP protocol stack that can give any microcontroller access to your WiFi network. The ESP8266 is capable of either hosting an application or offloading all Wi-Fi networking functions from another application processor. Each ESP8266 module comes pre-programmed with an AT command set firmware, meaning, you can simply hook this up to your Arduino device and get about as much WiFi-ability as a WiFi Shield offers (and that’s just out of the box)! The ESP8266 module is an extremely cost-effective board with a huge, and ever growing, community. This module has a powerful enough onboard processing and storage capability that allows it to be integrated with the sensors and other application-specific devices through its GPIOs with minimal development up-front and minimal loading during runtime. Its high degree of on-chip integration allows for minimal external circuitry, including the front-end module, which is designed to occupy minimal PCB area.
The ESP8266 supports APSD for VoIP applications and Bluetooth co-existence interfaces, it contains a self-calibrated RF allowing it to work under all operating conditions, and requires no external RF parts. There is an almost limitless fountain of information available for the ESP8266, all of which has been provided by amazing community support. In the Documents section below you will find many resources to aid you in using the ESP8266, even instructions on how to transform this module into an IoT (Internet of Things) solution!
 
                                                                      
                                                                      
                                                                     ** RELAY MODULE**

A relay is an electrical device that is generally used to control high voltages using very low voltage as a 35 Input. This consists of a coil wrapped around a pole and two small metal flaps(nodes) that are used to close the circuit. One of the nodes is fixed and the other is movable. Whenever electricity is passed through the coil, it creates a magnetic field and attracts the moving node towards the static node, and the circuit gets completed. So, just by applying a small voltage to power up the coil, we can actually complete the circuit for the high voltage to travel. Also, as the static node is not physically connected to the coil there is very less chance that the Microcontroller powering the coil gets damaged if something goes wrong. This is a four-channel relay board controlled by a computer USB port. The USB relay board is with 4 SPDT relays rated up to 10A each. You may control devices 220V / 120V (up to 4) directly with one such relay unit. It is fully powered by the computer's USB port. Suitable for home automation applications, hobby projects, and industrial automation. The free software allows one to control relays manually, create timers (weekly and calendar) and multivibrators, use date and time for alarms, or control from the command line. We provide software examples in Labview, .NET, Java, Borland C++, and Python.
 
                                                                    **CIRCUIT DIAGRAM**

We are controlling four relays in this IoT Home Automation System, each of which may control four appliances. The NodeMCU ESP8266 Wifi Module will receive data from the smartphone through the internet. The ideal IoT Platform is required to encode the ON/OFF signals and deliver them to the server and the ESP8266 Board. Also, the project needs internet access and cannot be executed without it. By using NodeMCU and the new CADIO app to control a 4-channel relay module from the manual switch & smartphone.
This ESP8266 control smart relay has the following features:

                                                     ●	Control home appliances with WiFi (CADIO app).
                                                     ●	Control home appliances with the CADIO web dashboard.
                                                     ●	Control home appliances with manual switches or push buttons.
                                                     ●	Monitor real-time feedback in the CADIO App.
                                                     ●	Control appliances without WiFi from manual switches.
 
                                                                         CADIO APP


CADIO is a complete home automation platform that allows you to build and control smart home devices, With many new features developed to give you the best smart home experience.

                                                                  Main CADIO features:
                                                                  ●	Very easy device configuration.
                                                                  ●	Control over local WiFi network.
                                                                  ●	Control over CADIO cloud.
                                                                  ●	New fully automated hybrid interface.
                                                                  ●	An unlimited number of devices can be added.
                                                                  ●	Support devices on different networks.
                                                                  ●	Units/Groups view.
                                                                  ●	Notifications for every device.
                                                                  ●	ON/OFF devices.
                                                                  ●	Dimmer devices.
                                                                  ●	RGB devices.
                                                                  ●	Shutters devices.
                                                                  ●	CADIO voice control (English & Arabic).
                                                                  ●	Timers.
                                                                  ●	Overheat protection/alarms.
                                                                  ●	Fan speed regulator.
                                                                  ●	Data devices.
 
                                                                            **SCREENSHOT**

                                                                  References & Bibliography:- Websites:
                                                                  •	http://www.iot-playground.com
                                                                  
                                                                  •	http://www.instructables.com
                                                                  
                                                                  •	http://en.wikipedia.org
                                                                  
                                                                  •	http://www.journals.elsevier.com/easyiot



                                                                       **Journals & other books**

1 . Kusuma S M, Assistant Professor, Department of telecommunication, MSRIT, Bangalore, India. “Home Automation Using Internet of Things.”
2. Niharika Shrotriya, Anjali Kulkarni, Priti Gadhave, International Journal of Science, Engineering and Technology Research (IJSETR), “SMART HOME USING WI-FI” • Anushri Aware, SonaliVaidya, PriyankaAshture, VarshaGaiwal PES’s Modern College of Engineering, Pune-04, International Journal of Engineering Research and General Science Volume 3, “Home Automation using Cloud Network”.











10
