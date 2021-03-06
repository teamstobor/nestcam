# NestCam

## Introduction

This project was made by Team# 684, [STOBOR](http://www.stobor.club). This project was part of First Lego League competition for Animal Allies season (2016-17).

## Purpose

Provide monitored nests for declining bird species. Collect data such as humidity, temparature inside and outside of the bird nests. In the future, make the nest cameras powered entirely by Solar power, use machine learning algorithms to identify presence or count of eggs,hatclings, identify bird species.

## Design

We followed the 8 step Engineering Design Process for our project. The following are the steps:

1. Identify the problem
2. Background research
3. Specify requirements
4. Design a solution
5. Make a prototype
6. Test the solution
7. If the solution does not meet the requirements, go back to step 5. and repeat.
8. Communicate results.

We adopted the above process from [Science Buddies](http://www.sciencebuddies.org/engineering-design-process/engineering-design-process-steps.shtml).

### Problem

About 3-6 billion trees are cut down each year in the world. 900 million of them in the US. About 13.7 million birds die each day in the US. In northeastern US, birds such as northen cardinal and american robin are declining each year in numbers.

### Background Research

#### Field trips

1. We went to Queens Aviary in Queens, NY. There we saw a variety of birds in their habitats.
2. We also went to Cornell Lab of Ornithology in Ithaca, NY. We made a presentation to a team of scientists and collected their feedback on our project. We went on several trails and saw birds of various species. 
3. Rochelle Tolkoff is bird expert who has been studying birds for over 20 years. She has two bird houses in her backyard.
4. Aashritha has 3 active bird nests in her backyard. She has been studying and collected data on various types of birds and their migration.

#### Websites

[Cornell Nestwatch](http://www.nestwatch.org) - 
We learned that different bird species have different nesting needs. Bird houses need to be of different shapes and sizes depending on the bird species. We learned how to collect data about bird's nesting habits. All of our team passed the NestWatch nest monitor exam and got certified.

[Raspberry Pi](http://www.raspberrypi.org) - 
Raspberry Pi is a small computer that has a camera connector, WiFi and Bluetooth. We learned how it works and how to use it for monitoring birds. We also bought one Raspberry Pi Zero W each for our team to learn how to program it.

[Sense HAT](www.raspberrypi.org/senseHAT) - 
SenseHAT is a small circuit board that has 64 LEDs (Light Emitting Diode), barometric pressure, temperature and humidity sensors. It sits on top of a Raspberry Pi.

[Node-Red](http://www.nodered.org) - 
This is a tool for programming the SenseHAT to collect data and draw graphs using its dashboard.

[PiBakery](http://www.pibakery.org/) - This software uses simple programming blocks to install Linux OS and settings on Raspberry Pi.

[Rpi Camera Web Interface](http://elinux.org/RPi-Cam-Web-Interface) - This is the software we used to show the output of camera on a web page. This is very easy to use but very powerful. This software contains many features to save video or pictures and use motion detection.

[Deforestation](http://time.com/4019277/trees-humans-deforestation/) - Billions of trees are being cut down every year leading to habitat loss for birds.

### Requirements

1. Need to be built out of wood. Plastic or other materials may harm birds.
2. Different sizes and shapes depending on bird species.
3. Need to have a small camera that is wireless with night vision. 
4. Need to be self powered like using a Solar panel. But initially, it could be powered by a battery and/or power cable. 

### Solution 

Using a Raspberry Pi 3 or Raspberry Zero W (which provides WiFi), a Raspberry Pi NOIR Camera, optionally with a SenseHAT and minimal setup/programming can provide a simple monitoring device. We built two carboard prototype bird houses to mount our camera setup. Currently we are making 3D Parametric models of bird houses that can be "printed" by a CNC machine on a 4 ft x 8 ft wooden plank. 

### Prototype

#### Parts

1. Raspberry Pi 3B or Raspberry Pi Zero W.
2. Raspberry Pi NOIR camera module with cable.
3. microSD Card with 8GB or more space.
4. Cardboard - preferably pizza boxes.
5. Scissors, Utility knife, Electric Tape and Duct tape. 

#### Instructions

1. Connect the camera to Raspberry Pi

2. Download and Install PiBakery from http://www.pibakery.org/download.html

3. In PiBakery, write a program to set up Wifi on First Boot. See example below:

![First Boot Program](images/pibakery_firstboot.png)

Replace **network-name** and **network-password** as per your home wifi setup. 

4. Insert microSD card into SDHC sleeve and insert that into PC/Laptop SDHC slot.

5. Format the microSD card.

6. In PiBakery, click on **Write**. 

7. Put the microSD card in Raspberry Pi 

8. Power up Raspberry Pi

9. Use [PuTTY](http://www.putty.org/) to connect to Raspberry Pi terminal

9. Follow installation instructions to install Rpi Web Cam : http://elinux.org/RPi-Cam-Web-Interface#Basic_Installation

10. Use a browser on your phone to connect to the ip-address of the raspberry pi. You should now see the video from the camera.

### Field Testing

#### Species

#### Locations




