# Istor-a

## Content (For storyboard):
* Storyboard Images :  
* The Great Diamond heist/Stealing the Diamond
Station 1 :
![Alt text](henrystdsb/station1.jpg)

<br>

Station 2:
![Alt text](henrystdsb/station2.jpg)

<br>

Station 3:
![Alt text](henrystdsb/station3.jpg)
<br>


<br>

Station 4 : 
![Alt text](henrystdsb/station4.jpg)

---
# **Setup Progress**

## **System Diagram for Video**

![Alt text](315Images/537%20video.png)

---
## **System Diagram for Audio**

![Alt text](315Images/Screenshot%202023-06-06%20152316.jpg)
![Alt text](315Images/537%20video%202.png)

---
## **System Diagram for Lighting**
![Alt text](315Images/Screenshot%202023-06-06%20152242.jpg)

---
## **System Diagram for Control**
* **Projector Control**
![Alt text](315Images/Screenshot%202023-06-06%20152331.jpg)

* **Phidget Sensor System Control**
![Alt text](315Images/Screenshot%202023-06-06%20152351.jpg)

---

## Floor Plan:
* **Overall Top View**
![Alt text](315Images/537.png)

* **Detailed Top View of 1 station**
![Alt text](315Images/537%20-%202.png)
![Alt text](315Images/537%20-3.png)

* **Detailed Side View of 1 station**
![Alt text](315Images/537%20side.png)

* **Detailed of the equipments (placed at both top corner of the room)**
![Alt text](315Images/537%20-4.png)

---

## Installation
### Video System

1) In our setup, we are using two laptops. 1 laptop per 2 stations. They are powered using the power adapter.

2) From 1 of our laptops, we connect via LAN cable to the Media Server.

3) In order to use Christie Pandora Box **( A projection mapping software )**, we require a licence for both the media server and the laptop.

4) From the Media Server, we had to use HDMI Extender **( Both TX and RX )** to one of the projector( 1st station ) via HDMI to LAN cable. Repeat the same step for the second projector( 2nd station ).

---


### Audio System

Switch on the power button of the Crown CT875 Amplifier. Wait for about a few minutes until the "signal" and the "ready" light lit up (in green)
![Alt text](315Images/photo_6053084928981186284_y.jpg)
![Alt text](315Images/photo_6053084928981186285_y.jpg)

Turn the Input Attenuation to 0 dB
![Alt text](315Images/photo_6053084928981186287_y.jpg)


---
### Lighting System
1) From our setup, we connect to the Light DMX Driver via HDMI to DMX cable. 

2) Ensure that there is power to power on the DMX Driver if not the light **(LED Strips)** would not be turned on. *[Light is mainly used to tell audience where the 1st station is till the end]*

---
### Control System
#### Phidget Control System
**In this setup, we will are using 2 phidget interface. The interface we are using is the phidget interface 8/8/8.**

##### Station 1
1) The sensors we have in station 1 are:
    - 1 Rotary potentiometer
    - 1 Button
    - 1 Phidget Advance servo 8-Motor
    - 1 RC servo motor

2) The phidget interface is connected to the laptop via USB-B to USB-A cable. We are using a usb extension in our setup 
   due to the location of where the phidget interface and laptop is place.

3) The phidget interface consists of 7 digital and analog inputs.

4) The Rotary potentiometer is connected to one analog input, the Button is connected to one digital input.

5) For the interactivity to work, we will be using an application called Widget Designer to program the button and sensor.

6) Program Files can be found under **WD Files** in this GitHub Repository

7) The Button is to enable for the video to start

8) While the Rotary potentiometer is there as a backup for the button, it also enables the content to be replayable 
  through our program.


##### Station 2
1) The sensors we have in 2 are:
    - 3 IR digital distance sensors
    - 1 Button
    - 1 Rotary potentiometer

2) The phidget interface is connected to the laptop via USB-B to USB-A cable. We are using a usb extension in our setup 
   due to the location of where the phidget interface and laptop is place.

3) The phidget interface consists of 7 digital and analog inputs.

4) The Rotary potentiometer is connected to one analog input, the Button is connected to one digital input.

5) The 3 IR sensors are connected to another 3 digital inputs. Each IR sensor is to one cue in the video timeline.

6) The Button is to enable for the video to start

7) While the Rotary potentiometer is there as a backup for the button, it also enables the content to be replayable 
  through our program.

8) For the interactivity to work, we will be using an application called Widget Designer to program the button and sensor.

9) Program Files can be found under **WD Files** in this GitHub Repository


---
## Operational Phase:
### Christie Pandora Box

1) **After downloading the Christie Pandora Box and Christie Pandora Server Management, you would need to buy the licence in order to run the pandora box**

2) **After having both the licence and the pandora box, open up the pandora server management, in the server management, you need to open the media server *(Direct connection from laptop to the media server with licence)*.**

3) **Afterwards, you can open the Pandora Box application, both laptop and the server management, create new project, and add video assets into the media server. Ensure that the video assets are on different layers and that the layers are not hidden**

4) **In order to mesh the video output to fit the screen output, you would need to right click on the folder, rename it for easy recognition, and mesh it to fit the screen that you are projecting the video onto.**

---
## **Props used for interaction**

1) **The props below is for the audience to use to interact when they have to select different options to progress the storyline**

2) **The pickaxe is used to proceed the storyline(the right answer).**

3) **The other 2 options are the wrong answers where the video will proceed to play other scenerios until the right answers are chosen.**

![Alt text](Interactimg/IMG20230606154514.jpg)

* The button below is used for audience intraction, to start the sequence of the video

![Alt text](Interactimg/IMG20230606160140.jpg)

---
## Testing Phase
---

![Alt text](henrystdsb/henrystd.jpg)
### **Stealing the Diamond**
1) You are playing as the main character(Henry Stickmin). After the events of Escaping the Prison, you are resting at home. 

2) You tune in to the television where you see the mayor annoucing the grand opening of the new museum. Within the new exhibits sits a priceless diamond.

3) Knowing the value of the diamond, you sought to steal the diamond to pay off his late rent of his house.

4) You will be given several options to choose from to aid your character to successfully steal the diamond.
---
## Troubleshooting
---