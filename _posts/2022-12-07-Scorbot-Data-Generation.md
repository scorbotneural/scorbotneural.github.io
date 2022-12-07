---
layout: post
title: "Scorbot Data Generation"
author: "Ryshant Padarath & Sherlin Chand "
categories: facts
tags: [sample]
image: EB42C33E-0A69-4A58-A050-D2A0F4999E74.jpeg
---

##Data Generation 

1)	Data Generation is the first part of this project, the group utilized a Matlab toolbox available online that is specific for SCORBOT-ER-4U. MTIS toolbox and Kutzer toolbox was carefully studied and then it was decided that Kutzer toolbox will be used to find the forward kinematics and inverse kinematics of the Robotic arm. 

2)	Angles in the interval of one was chosen for each of the joints and the joint are as specified and the robotic arm constraints was also taken into consideration.


| Joint  |  αi (rad)     |
| ------------- | ------------- |
| 1      | pi/2 |
| 2      | 0    |
| 3      | 
| 4      |


Joint 	αi (rad)	ai (mm)	di (mm)	Operating Range (o)
1	 	16	364	-155 to 155
2	0	220	0	-35 to 130
3	0	220	0	-130 to 130
4	 	0	0	-130 to 130
5		0	145.125	-570 to 570



Table 2 was used to utilize the operating ranges of the SCORBOT-ER-4U, which means that while generating the forward and inverse kinematics, the operating ranges should not exceed the operating ranges as it might harm the robotic arm while being in the middle of the movement. 
