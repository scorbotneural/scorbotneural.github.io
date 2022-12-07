---
layout: post
title: "Scorbot Data Generation"
author: "Ryshant Padarath & Sherlin Chand "
categories: facts
tags: [sample]
image: CF1013FF-47FB-42AC-8FEA-5FA0F11FABE0.jpeg
---

#Data Generation 

1)	Data Generation is the first part of this project, the group utilized a Matlab toolbox available online that is specific for SCORBOT-ER-4U. MTIS toolbox and Kutzer toolbox was carefully studied and then it was decided that Kutzer toolbox will be used to find the forward kinematics and inverse kinematics of the Robotic arm. 

2)	Angles in the interval of one was chosen for each of the joints and the joint are as specified and the robotic arm constraints was also taken into consideration.

Table 1 was used to utilize the operating ranges of the SCORBOT-ER-4U, which means that while generating the forward and inverse kinematics, the operating ranges should not exceed the operating ranges as it might harm the robotic arm while being in the middle of the movement.

| Joint 	| αi(rad) 	| ai(mm) 	| di(mm)  	| Operating Range(o) 	|
|-------	|---------	|--------	|---------	|--------------------	|
| 1     	| Pi/2    	| 16     	| 364     	| -155 to 155        	|
| 2     	| 0       	| 220    	| 0       	| -35 to 130         	|
| 3     	| 0       	| 220    	| 0       	| -130 to 130        	|
| 4     	| Pi/2    	| 0      	| 0       	| -130 to 130        	|
| 5     	| 0       	| 0      	| 145.125 	| -570 to 570        	|

Table 1 : Forward kinematics modeling.

3)	After the operating ranges (angles) were identified, X and Y coordinates were obtained with respect to the angle ranges. For example, joint 1 (base) had the operating range from -155 to 155 and the X and Y coordinates corresponding to the operating angles.

4)	Utilizing the Kutzer MATLAB toolbox, the command ScorbaseBSEPR2XYZPR was utilized to find the forward kinematics of the model, once the forward kinematics has been found, the data was stored as a MAT file that can be used later without running the whole program again.

5)	Once the forward kinematics data was stored, the team utilized the MATLAB command ScorXYZPR2BSEPR to find the inverse kinematics of the model. The obtained data was again stored as a MAT file. 

6)	Since the data was quite large for MATLAB to handle, the team decided to store the data in several portion. The information of the dataset stated that there are 5 features and 453871 observations for the forward kinematics and 5 features and 453871 observations for inverse kinematics. 

---
image : figure1.jpeg
---
![alt text](https://github.com/scorbotneural/scorbotneural.github.io/blob/gh-pages/assets/img/109DD180-034F-4DB1-857A-743B850836FD.jpeg "Millennial Demo Image")
