---
layout: project
type: project
image: images/wireless-farming.jpg
title: Wireless Sensor Network for Use in Automated Farming
permalink: projects/cotton
# All dates must be YYYY-MM-DD format!
date: 2017-02-11
labels:
  - C++
  - Arduino
  - Embedded System
summary: This group project aims at using available technology to automate farming and reduce crop failure.
---

This project got started because we see the impact it can have in fostering Hawai’i agriculture and sustainability. 
According to Robert Mendelsohn, an environmental economics professor at Yale University, he said that around 39% crop failure rates in the US was the result of soil and climate (Mendelsohn). Since this was the case, the farm sensors device could help notify farmers the changes in the surrounding environment, and so act proactively. Having this kind of technology would not only remove fear out of the unpredictability of the changes in weather, it will also put the farmers in the offensive line against crop failures instead of in the defense.

Providing the information that farmers wants to know to better protect and prosper their crops is what we want our farm sensors to be able to do. In order to produce such device, we uses the arduino systems. They allow us to customize which sensor we want to be included and how each one functions. The behaviors of the device are controlled by the coding in Arduino IDE. The main board that we use is Adafruit Feather M0 Radio with LoRa radio module. With the ability to communicate with other microcontrollers via radio frequency, the Adafruit Feather can send and receive the condition of the farm from other sensors in the field. As of right now, the two sensors that we use are the temperature sensors and light sensors. Additional sensors can be easily added to meet the demand of each customer.

Here are the pictures of the parts that we use:

![aa](https://cloud.githubusercontent.com/assets/21114221/23250210/29c6e754-f94c-11e6-8521-023e7ab9a56c.png)

This is the Transmitter Feather. As of for now, it is equipped with light sensors and temperature-humidity-pressure sensors. These sensors will pick up information around the surrounding.

![ff](https://cloud.githubusercontent.com/assets/21114221/23250360/e24c0048-f94c-11e6-8d1a-456643099a68.png)
The Transmitter Feather is equipped with Lithium battery and solar panel. The Solar Panel powers the feather and charge the battery during daytime, so that when night time comes, or during cloudy/rainy day, the feather can be powered by the battery.

![receiver board feather](https://cloud.githubusercontent.com/assets/21114221/23250383/03df136c-f94d-11e6-88e7-c5c3d4cba7fe.png)
This is the Receiver Feather. It will receive all the environmental data that the transmitters pick up in the surrounding.

![distance the sensors can communicate with obstacles](https://cloud.githubusercontent.com/assets/21114221/23250399/173aa03e-f94d-11e6-905b-b898bb67138f.PNG)

The two feathers can communicate with each other at the maximum of 226m if there are obstacles in the surrounding. This location is in Kapiolani Community College.

![distance the sensors can communicate without obstacles](https://cloud.githubusercontent.com/assets/21114221/23250413/24c5cc7e-f94d-11e6-8e0b-45dd668b4d00.PNG)

The two feathers can communicate with each other at the maximum of 1.09km (or 0.6 miles) when there are no obstacles around. This location is in Kahala beach park.

We now have a well-functioned prototype to demonstrate how the device works. If we get a chance to continue this project, we will develop a more user-friendly interface for the customers to read the information about their farms that the sensors pick up. Given enough resources and adequate skills, we would love to develop an artificial intelligent algorithms that can self-govern the whole farm, such as automatically provide extra water to the soil on very sunny day, release adequate fertilizers when the soil needs, identify early stages of harmful disease displayed in plants and warn the farmers.

You can learn more at https://github.com/thinhtedlam/Wireless-Sensor-Network-for-Use-in-Automated-Farming
