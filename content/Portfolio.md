# Academic Work

### CAL Poly Switch
**2023-2025**

My masters thesis was creating a robot application using ROS2 and ROS2 control for a custom robot quadruped, the Cal Poly Switch. Developing Switch took place on all levels of the stack from machining aluminum stiffeners for the frame to integrating a digital twin with Foxglove interfacing with ROS2.


![[1000009137.jpg]]
Switch internals with Jetson, power distribution, battery, and motors. 

![[BasicIMU_Foxglove.png]]
Foxglove interface with sensor readouts and digital twin.

### Planerizer
**2023-2024**

On arriving at Cal Poly I assisted with the redesign, and manufacturing of a leg test stand for my now dear friend John Bennett's thesis. Our running joke was senior projects get $5000 and a year, and as masters students we got $500 and 3 months. 

The planerizer redesign was a resounding success, with minimal backlash and deflection through the use of compression joints, and a thin wall aluminum rectangular tubing. The new design was machined and assembled in time for [John's masters thesis testing](https://digitalcommons.calpoly.edu/theses/2891/). 
![[planerizer.png]]
### Micro-Mouse
**2023-2023**
For my ME507 robotics design class project, myself and my partner made  a custom 2 wheel micro-mouse robot for maze solving using an ESP32 feather. The mouse contained an IMU, a TOF sensor, 2 IR sensors, and 2 motors controlled using a dual H bridge. I soldered and promptly debugged the PCB for test day. Additional functionality was added with a web sockets interface to access state and control information for the robot. 

### S.L.A.P. X-ray Spectroscopy Alignment
**2022-2023**

![[Pasted image 20250804175354.png]]

For my senior project we were tasked with building a proof of concept test stand for x-ray spectroscopy for the Stanford Linear partial Accelerator Center (SLAC). Our task was to use two 6-axis robotic arms to position spherically ground crystals for the x-ray spectroscopy process. 

Our stand had to reflect and focus the beam on to a 1 mm detector, across a distance of 1 meter. The arms and detector then would sweep through a series of positions and would need to remain synced. I wrote the Spiral Linear Alignment Procedure (SLAP) using OOP and multi-threading for the alignment of the robotic arms. The arms first moved into their theoretical perfect position, then spiraled outward while light intensity was recorded by the detector. Once a peak was found, the system moved from the center of the spiral to the peak intensity point until a new peak intensity was found. 

The system was completely wireless with the admin laptop, robotic arms, and esp8266 connected to a router. The laptop ran RoboDK with a python application interfacing with the arms and webserver hosted by the esp8266. The 8266 connected to the photo detector and stepper motor and would move the motor and relay light intensity and motor position upon http methods utilizing json. 
![[20230413_184722.jpg]]
Robots with crystals installed.

![[20230410_205725.jpg]]
Alignment of the beam on the move-able detector with a humidifier to show the light beam.
#### Spiral Alignment Proof of Concept
![[Pasted image 20250804151928.png]]
The SLAP was first theorized and tested using MATLAB simulations.
## Interesting Bugs: Sparse Sampling on a Dense Spiral
An interesting bug arose when doing a sparse linspace on a comparatively dense spiral.
![[Pasted image 20250804151933.png]]



## Research: Modal Analysis on 3D printed parts
**2022-2023**


My undergrad research project was attempting to identify defects commonly found in 3D printed metal parts using modal analysis. Me and my partner started undergraduate research back up at Chico State with this project. We were told that we were the first paper in at least 20 years to come out of the Chico State ME department, and they couldn't give us the exact number because the records did not got further.

Our paper [Investigations on Natural Frequency Shifts of a Cantilever Beam With a Spherical Void Defect](https://asmedigitalcollection.asme.org/ssdm/proceedings-abstract/SSDM2023/87141/V001T03A002/1169180) attempted to model the effects of a point void in a homogeneous beam using Euler Bernoulli Beam theory and was presented at in 2023 and published to ASME Aerospace Structures, Structural Dynamics, and Materials Conference. 

![[20230224_170049.jpg]]



### Adjustable Coffee Grinder: Machine Design Final
**2021-2021**
For my ME340 final, our task was to design, and build a hand operated coffee grinder using a burr grinder set. I machined the components using 3 axis CNC and manual milling, and welded the frame using TIG. Fun fact, the project was in a backpack and stolen from my car so I had to re-machine and re-weld the whole assembly. Luckily I worked out the tool paths on the first run.

![[Pasted image 20250804151859.png]]
CNC machined aluminum body and gear box, manual machined steel base, PLA printed accessories with TIG frame and handle with walnut inlay.
![[Pasted image 20250804151907.png]]
## Industry

### Zomes
#### 5 Axis Contractor
**2021-2021**
![[Pasted image 20250804152037.png]]

Over the Summer of 2021 I worked as a 5 axis machining contractor at Zomes in Petaluma California. The following photos are parts I machines using a 5 axis Motionmaster CNC I got up and running.

 **Skills**
- 5 axis machining
- Machining composites
- Machining for casting
- Troubleshooting a 5 axis mill
 - 5 axis post processor editing

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfy_141bL9x9tlga8CJMYJgkOHoPBt6Ycto9GmiFgRDOT-kDeYPw3E7OlXvzdJ5YHrrapB-e859HCLpI7PoX5_4wSc50-ZIeZY-TdO1OMk5wiT6AXnktIljOXkABlfzqycDeyTMkkqqDyOQPhAm5ub2QRY?key=a41sPQzYO4lavnvk9vP1LdqX)
![[5AxisPart.png.png]]

![[Pasted image 20250804151537.png]]
![[Pasted image 20250804151544.png]]
Completed 5-axis mold.

![[Pasted image 20250804151557.png]]
Silicone casting with completed concrete panel (keys for scale).
## AVL Looms
#### Welding and CNC Intern
**2020-2020**
![[Pasted image 20250804151550.png]]
Over the Summer of 2020 I got a CNC and MIG welding internship at AVL Looms in Chico California. The following photos are parts I milled on the CNC, welded, or both.

**Skills**
- Stock cutting to 1/64”
- Multi job CNC milling
- Multi tool jobs
- Toolpath generation
- Fixturing
- MIG welding

![[Pasted image 20250804151603.png]]

![[Pasted image 20250804151608.png]]
![[Pasted image 20250804151614.png]]

Welding end caps on 20' members was a bit nerve wracking on the first part, but it became old hat.

## Chico State Baja
**2019-2020**

![[Pasted image 20250804151643.png]]
![[Pasted image 20250804151651.png]]![[Pasted image 20250804151656.png]]

## Personal Projects
**2020**
## Skate Board Stand
![[Pasted image 20250804151708.png]]![[Pasted image 20250804151711.png]]


![[SkateBoardStandSkateboards.png.png]]

## Collapsible Guitar Stand
**2021**
![[Pasted image 20250804151806.png]]![[Pasted image 20250804151813.png]]![[Pasted image 20250804151819.png]]
![[Pasted image 20250804151826.png]]![[Pasted image 20250804151833.png]]

## Stage Jewelry Box 
**2022**

![[Pasted image 20250804151917.png]]

![[Pasted image 20250804151848.png]]

