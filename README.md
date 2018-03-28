# UR-Conveyor-phone_recognition
Includes files for Recybot project, skoltech

Recybot: is the brainchild of prof. Dzmitry Tsetserukou and MIT Professor Kamal Youcef-Toumi 2015
Aim: disassemble mobile phones to get the valuable minerals like gold, silver, ...etc

Recybot consist of the following SubSystems :
1- two delta robots,
2- two universal robots (URs),
3- two camera recognition systems, 
an industrial conveyor.

For more information about Recybot, please visit: 
http://www.skoltech.ru/en/2017/10/skoltech-shows-off-high-caliber-of-russian-robotics-at-a-major-international-youth-festival/ 


In this rep you find files related one of the URs and the industrial conveyor subsystems. The following is a short description 

# STM32(1).hex  
contains the source code for the configuration and low level programming of the STM32F4. To flash this code to the STM32F4 you should use STlink utility.
# Test_communication.ipynb
(requires further developement)
Contains the protocol for controling the conveyor with three main functions
1- set_speed(v)- sets the speed
2- move(dx,v)- this function moves the conveyor dx cm with speed v
3- get_status()- gets the current position of the conveyor (need debugging in the low level code(STM32))

# UR_conveyor 
contains python code for controlling the UR robot to follow a certain object using an RGB camera and some OpenCV liberaries


# Conveyor_node 


# Phone_recognition 

# UR_node


