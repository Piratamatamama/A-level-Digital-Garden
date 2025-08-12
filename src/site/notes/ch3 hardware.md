---
{"dg-publish":true,"permalink":"/ch3-hardware/"}
---

- [[#1. Memory & Storage Device|1. Memory & Storage Device]]
	- [[#1. Memory & Storage Device#1. Primary memory|1. Primary memory]]
		- [[#1. Primary memory#1. RAM|1. RAM]]
			- [[#1. RAM#DRAM vs SRAM|DRAM vs SRAM]]
		- [[#1. Primary memory#2. ROM|2. ROM]]
			- [[#2. ROM#PROM vs EPROM vs EEPROM|PROM vs EPROM vs EEPROM]]
	- [[#1. Memory & Storage Device#2. Secondary Memory|2. Secondary Memory]]
		- [[#2. Secondary Memory#1. Magnetic|1. Magnetic]]
			- [[#1. Magnetic#HDD|HDD]]
		- [[#2. Secondary Memory#2. Solid State (control movemnt of electrons in flash memory)|2. Solid State (control movemnt of electrons in flash memory)]]
			- [[#2. Solid State (control movemnt of electrons in flash memory)#SSD|SSD]]
			- [[#2. Solid State (control movemnt of electrons in flash memory)#NAND vs NOR|NAND vs NOR]]
		- [[#2. Secondary Memory#3. Optical(laser light)|3. Optical(laser light)]]
			- [[#3. Optical(laser light)#CD vs DVD vs BLU-RAY|CD vs DVD vs BLU-RAY]]
- [[#2. Input & Output Devices|2. Input & Output Devices]]
		- [[#2. Secondary Memory#1. printers|1. printers]]
		- [[#2. Secondary Memory#1. laser printer|1. laser printer]]
		- [[#2. Secondary Memory#2. inkjet printer #card|2. inkjet printer #card]]
		- [[#2. Secondary Memory#3. 3d printer|3. 3d printer]]
		- [[#2. Secondary Memory#2. Speakers and microphone|2. Speakers and microphone]]
			- [[#2. Speakers and microphone#Speaker|Speaker]]
			- [[#2. Speakers and microphone#Microphone|Microphone]]
		- [[#2. Secondary Memory#3. Touchscreen|3. Touchscreen]]
		- [[#2. Secondary Memory#4. VR virtual reality headset|4. VR virtual reality headset]]
		- [[#2. Secondary Memory#5. Sensor and monitoring, control system|5. Sensor and monitoring, control system]]

### 1. Memory & Storage Device
#### 1. Primary memory
##### 1. RAM
- memory that can be directly access from CPU
- also called **Physical Memory** – because it refers to actual hardware (the RAM chips) installed in the system.
###### DRAM vs SRAM

| No. | Feature             | Dynamic RAM( DRAM)                                                                      | Static RAM (SRAM)                                              |
| --- | ------------------- | --------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| 1   | Memory Element      | Transistor act as switch, Capacitor store binary bits                                   | Flip Flop![[Pasted image 20250425101653.png\|Pasted image 20250425101653.png]]                  |
| 2   | Refresh requirement | need constant refreshing                                                                | no need constant refreshing                                    |
| 3   | Cost                | less expensive                                                                          | more expensive                                                 |
| 4   | Speed (Access time) | Slower access time                                                                      | Faster access time                                             |
| 5   | Power consumption   | consume more power than SRAM at normal access speed, as need to be constantly refreshed | can consume more power than DRAM if accessed at high frequency |
| 6   | memory capacity     | higher memory capacity                                                                  | lower memory capacity                                          |
| 7   | typical usage       | main memoery                                                                            | memory cache in processor                                      |
##### 2. ROM
###### PROM vs EPROM vs EEPROM

| No. | Feature                     | PROM            | EPROM                             | EEPROM                                                                    |
| --- | --------------------------- | --------------- | --------------------------------- | ------------------------------------------------------------------------- |
| 1.  | write capability            | write once only | can be overwritten multiple times | can be overwritten multiple times                                         |
| 2.  | erasing method              | not erasable    | UV light                          | electrical signal                                                         |
| 3.  | need to remove from circuit | not erasable    | need to removed from device       | can be erased in situ                                                     |
| 4.  | rewriting flexibility       | not erasable    | must erase all before rewriting   | selective rewriting, does not have to be entirely erased before rewriting |

#### 2. Secondary Memory
##### 1. Magnetic 
###### HDD
##### 2. Solid State (control movemnt of electrons in flash memory)
###### SSD
###### NAND vs NOR

| Feature    | NAND                     | NOR(eeprom)                |
| ---------- | ------------------------ | -------------------------- |
| Acess type | Block access(page level) | Byte-size access           |
| Read Speed | Slower                   | Faster                     |
| Capacity   | Higher                   | Lower                      |
| Use Case   | Data Storage(USB,SSD)    | Code Storage(EEPROM, BIOS) |
| $          | Cheaper                  | More expensive             |

##### 3. Optical(laser light)
1. Type: Optical Storage(use laser light to read and write data)
2. Storage: Data is stored as pits and bumps on a spiral track from centre to edge
3. Read/ Write: Laser beam reflects off disk surface to detect the pattern of pits
4. Data Capacity factor: Shorter laser wavelength allows smaller pits and tighter tracks, increasing storage
5. Layering: Birefringes

Red wavelength = longer wavelength = larger pits, loose tracks = storage decrease
Blue wavelenth = shorter wavelengh = smaller pits, tighter tracks = storage increase
###### CD vs DVD vs BLU-RAY

| Feature            | CD      | DVD                 | Blu-Ray  |
| ------------------ | ------- | ------------------- | -------- |
| Laser colour       | Red     | Red                 | Blue     |
| Laser wavelength   | 780 nm  | 650 nm              | 405 nm   |
| Storage capacity   | 700 MB  | 4.7 GB              | 25 GB    |
| Disk construction  | single  | two (birefringence) | single   |
| Track Pitch        | 1.60 µm | 0.74 µm             | 0.30 µm  |
| Data layer tech    | Large   | Smaller than CD     | Smallest |
| Read/ Access Speed |         |                     |          |
| Encryption         | Basic   | CSS                 | AACS     |
|                    |         |                     |          |

### 2. Input & Output Devices
##### 1. printers
##### 1. laser printer 
![image-2.png|285x285](/img/user/image-2.png)
Main idea
- powder ink
- static electricity
- print whole page in one go
- 4 toner: KCMY: Black Cyan Magenta Yellow
Preparation Stage
1. data from document sent to <u>printer driver</u>
2. printer driver is a software that  ensure data is in a format that printer can understand/ ensure correct file format
3. check printer availability
4. data sent to printer, stored in temporary memory called <u>printer buffer</u>
Printing Stage
5. drum made positively charged
6. laser beam scan negative area of exact image on drum
7. positive toner stick to negative area of drum
8. positive toner stick to (more) negative paper when rolled in
Fusing and Cleaning Stage
9. roller with fuser heat paper so that ink stick firmly to paper
10. lamp discharges the drum for next print
![Pasted image 20250412121317.png|413x224](/img/user/Pics/Pasted%20image%2020250412121317.png)
![image.png|412x240](/img/user/image.png)
![image-1.png|417x217](/img/user/image-1.png)

| jargon                    | description                                                                                                |
| ------------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Laser printer**         | A type of printer that uses powdered ink (toner) and a laser to print a whole page at once.                |
| **Printer driver**        | Software on computer that converts your document into a format that the printer can understand.            |
| **Printer buffer**        | Temporary memory in the printer where print data is stored before printing starts.                         |
| **Drum**                  | A rotating cylinder in the printer that gets charged and attracts toner to create the image.               |
| **Laser beam**            | A light beam that removes charges from certain parts of the drum to form the pattern of the image or text. |
| **Toner (powdered ink)**  | Positively charged ink powder that sticks only to the negatively charged areas of the drum.                |
| **Negative paper**        | Paper that is given a negative charge to attract the toner from the drum.                                  |
| **Fuser (heated roller)** | A component that uses heat to melt the toner so it bonds permanently to the paper.                         |
| **Discharge lamp**<br>    | A lamp that removes leftover electric charges from the drum to prepare it for the next page.               |

##### 2. inkjet printer #card
![image-3.png|0x0](/img/user/image-3.png)
Main idea
- droplets of ink 
- sprayed using nozzles on print head
- ![image-6.png|290x181](/img/user/Pics/image-6.png)
- 2 seperate ink cartridge:
	1. BYM  Blue, Yellow, Magenta
	2. Black cartridge
	3. ![image-5.png|310x204](/img/user/Pics/image-5.png)
- stepper motor and belt to move print head acroos page side to side
- paper feed tray
Technology
	1. Piezoelectric
		- crystal located at ink reservoir
		- crystal given electric charge that made it vibrate
		- vibration force ink out to paper
		- ![image-13.png|398x227](/img/user/Pics/image-13.png)
		- ![image-14.png|396x259](/img/user/Pics/image-14.png)
		- ![image-15.png|225x253](/img/user/Pics/image-15.png)
	2. Thermal bubble
		- tiny resistor create heat which makes ink vaporise
		- ink form tiny bubble
		- bubble expand, cause ink ejected onto paper
		- when bubble collapse, vacuum cause fresh ink to be drawn to print head
		- ![image-9.png|324x331](/img/user/Pics/image-9.png)
		- ![image-7.png|279x280](/img/user/Pics/image-7.png)
		- ![image-10.png|394x255](/img/user/Pics/image-10.png)
Preparation Stage
1. data of document sent to printer driver
2. driver ensure the document is in correct file format that the printer can understand
3. check printer availability
4. data sent and stored in temporary storage ( printer buffer)
Printing Stage
	1. sensor detect whether there is paper in paper feed tray
	2. print head move side to side across paper
	3. four ink colour spray in exact amount to produce final colour
	4. at the end of each full pass, the paper is advanced slightly to allow next line printing, continues until whole page printed
End Stage
5. check printer buffer, if there is more data, then process from 1 to 4 repeated until buffer empty
6. printer send interrupt to computer processor when buffer empty to request more data
	
![image-12.png](/img/user/Pics/image-12.png)



##### 3. 3d printer
![image-4.png|420x420](/img/user/image-4.png)
1. additive manufacturing: object is built up layer by layer
2. powdered resin, powdered metal, ceramic

data processing stage:
1. The object is designed using Computer Aided Design (CAD) software
2. The software splits the object into slices
3. The data about the slices is sent to the printer
Technology

| Direct print                                                                   | Binder print                                                                 |
| ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------- |
| 1. The solid plastic is melted and transferred to the nozzle<br><br>           | 1. first pass spray dry powder                                               |
| 2. a stepper motor that ca move left right up down move the nozzle to position | 2. second pass a binder(glue) is spray onto the powder to form a solid layer |
| 3. nozzle extrude molten plastic                                               | 3. Uv/ laser light cool harden                                               |
| 4. step 2 to 3 is repeated until layer is completed                            |                                                                              |
| 5. fan cools layer                                                             |                                                                              |


##### 2. Speakers and microphone
- transducer: change one type of energy into another type of energy
###### Speaker
(digital-> analogue)

digital to analogue stage
1. digital file stored binaries are translated to analogue current using DAC
2. current are amplified and sent to speaker

speaker internal operations:
	1. current flows through coil of wire
	2. current in coil creates electromagnetic field
	3. changes in audio causes the direction of electrical currrent to change( AC current), which determines the polarity of electomagnet
	4. wire move past a permanenet magnet
	5. changes of polarity of electromagnet cause it to repelled by and attracted to permanent magnet
	6. this movement is vibration that causes the cone to vibrate
	7. diaphragm vibrate, producing sound waves

![image-18.png](/img/user/Pics/image-18.png)

![image-20.png](/img/user/Pics/image-20.png)
![image-21.png](/img/user/Pics/image-21.png)
![image-22.png](/img/user/Pics/image-22.png)

 ###### Microphone 
 (analogue -> digital)
 
 1. Microphone has a diaphragm
2. Incoming sound waves cause vibrations of cone
3. Coil attached to cone cause the coil to move past a magnet
4. Coil cut the magnetic field lines of permanent magnet,(cause a change in m-flux linkage that) cause induced current flow in coil  ( to oppose the change that produce it)
5. AC current is produced  
6. The shape of the current waveform matches the shape of the original sound wave — it’s an electrical analogue equivalent of the sound.![image-19.png](/img/user/Pics/image-19.png)
 
##### 3. Touchscreen
![image-17.png](/img/user/Pics/image-17.png)

| Capacitive                                                                 | Resistive                                                                                   |
| -------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| multi-layered glass forming capacitor grid                                 | top layer is flexible plastic, air gap exist between plastic and bottom glass layer         |
| when finger(conductor) touch screen, it alters screen'selectrostatic field | when finger touch screen, top layer move to touch bottom layer, which completes the circuit |
| coordinate of the point of contact is calculated                           | coordinate of point of contact is calculated                                                |
| coordinates sent to touchscreen driver                                     | coordinates sent to touch screen driver                                                     |
| 1. cannot used with gloved hand                                            | 1. not clear under strong direct sunlight                                                   |
| 2. only special stylus can be used                                         | 2. screen can malfunction due to long-time strong pressing against top layer                |
| a. no need to press hard onto screen to register point of contact          | a. can use with all types of stylus, including gloved hand                                  |
|                                                                            | b.                                                                                          |



##### 4. VR virtual reality headset
![image-41.png](/img/user/Pics/image-41.png)

| Feature                   | How                                                                                     |
| ------------------------- | --------------------------------------------------------------------------------------- |
| 1. Video Input            | - video sent from HDMI connected to computer/smartphone in headset                      |
| 2. Video Display          | -LCD/OLED                                                                               |
| Lenses                    | Lenses reshape and focus image for 3D effect                                            |
| 3. Field of View          | 110 degree field of view(pseudo 360)                                                    |
| 4. Head Movement Tracking | -Sensors (gyroscope/accelerometer) track movement of head to match video feed           |
| 5. Sound                  | Binaural sound for 3d effect                                                            |
1. IMAGE/VIDEO INPUT
   - Video sent from computer (HDMI) or smartphone in headset.

2. DISPLAY
   - LCD or OLED screens.
   - Two feeds: one for each eye.
   - Lenses reshape and focus image for 3D effect.

3. FIELD OF VIEW & FRAME RATE
   - 110° field of view (pseudo 360°).
   - 60 to 120 frames per second.

4. HEAD MOVEMENT TRACKING
   - Sensors: gyroscope and accelerometer.
   - LEDs + cameras for precise movement tracking.

5. SOUND
   - Binaural (3D surround) sound.
   - Audio appears from sides, behind, or distance.

6. EYE TRACKING (optional)
   - Infrared sensors monitor eye movement.
   - Depth of field changes based on eye focus.

##### 5. Sensor and monitoring, control system 

| Monitoring system                                                                   | Control system                                                                               |
| ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| sensor detects reading of sensor to see if it matches desired value                 | sensor detects reading of sensor to see if it matches desired value                          |
| system/ processor records feedback                                                  | system produce an action using actuator                                                      |

| if data is outside of acceptable range, a warning message is sent / alarm activated | if data outside acceptable range, processor send signals to actuators( control valve/ motor) |
| ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| processir has no effect on what is being monitored, only watching                   | output from system affects the next set of inputs from sensor                                |
