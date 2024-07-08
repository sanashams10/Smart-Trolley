![image](https://github.com/sanashams10/Smart-Trolley/assets/175038496/6c941875-6455-4b96-8cb4-b5b05cf04fbb)# Smart-Trolley
The Smart Trolley, using Arduino Uno and external motors, interfaced with a Bluetooth module as controller, to usher in the next age revolution, inclusivity-centered automation in India, especially driven for the citizens of age or PWD. 

As a country that houses one of the highest number of senior citizenship and people with disabilities that make it challenging for them to be part of these growing industries, they need to be represented and stood up for, considering travel and groceries would be included in primary commodities of necessity.  It is due to these barriers of old age and physical or neurological obstacles, they are struggling in their mundane, day-to-day activities, especially in areas of carrying something as heavy and bulky as luggage trolleys or supermarket carts. 
 
This paper, therefore aims to consider the challenges and problem statement and devise a solution centric approach to the world of automation. Using this assistive technology, the working, daily activities and long term sustainability of these people can be achieved. 


I.	DESIGN AND CONFIGURATION
The smart trolley is simply an automated assembly of the electronic and mechanical components, namely: a pair of external motors attached to the rotary wheels of the trolley to allow controlled and directed movement as per instruction, a Bluetooth module interfaced with RC Controller that works in tandem with a smartphone and is used via software to control and maneuver the movements, with the help of pre-programmed, manually hardwired and therefore, configurable code in Arduino Uno. The gestures controls at the RC Controller app sends control signals to the Arduino Uno through the interfaced Bluetooth module in a range of 10m. The Arduino Uno reads the aforementioned real-time commands and executes the desired movement by sending digital signals to the motor driver.

II.	WORKING
The working mechanism behind the smart trolley can be easily divided into three header blocks of the input, controller and the output. The input includes the RC Controller and the Bluetooth module in the smartphone application that provides the directions for the desired movement. The Bluetooth module relays these commands up to a range of 10m. The controller unit is managed by the Arduino, that reads the received command and controls the movement by direction the motor controller. The output is given by the interfaced motor controller that directs the external motors to actuate, according to the commanding current, voltage and directionality in linear or sideways motions. On encountering an obstacle within  a range of     , a buzzer sound will be generated to alert the consumer and provide further aid in the carriage of luggage/commodities. 



