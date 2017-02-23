# Wireless-Sensor-Network-for-Use-in-Automated-Farming

The reason why my team and I decided to choose this project was because of the potential it had in fostering Hawai’i agriculture and sustainability. According to Robert Mendelsohn, an environmental economics professor at Yale University, he said that around 39% crop failure rates in the US was the result of soil and climate (Mendelsohn). Since this was the case, the farm sensors device could help notify farmers the changes in the surrounding environment, and so act proactively. Having this kind of technology would not only remove fear out of the unpredictability of the changes in weather, it will also put the farmers in the offensive line against crop failures instead of in the defense.

Providing the information that farmers wants to know to better protect and prosper their crops is what we want our farm sensors to be able to do. In order to produce such device, we uses the arduino systems. They allow us to customize which sensor we want to be included and how each one functions. The behaviors of the device are controlled by the coding in Arduino IDE. The main board that we use is Adafruit Feather M0 Radio with LoRa radio module. With the ability to communicate with other microcontrollers via radio frequency, the Adafruit Feather can send and receive the condition of the farm from other sensors in the field. As of right now, the two sensors that we use are the temperature sensors and light sensors. Additional sensors can be easily added to meet the demand of each customer.

Here are the pictures of the parts that we use:

![]({{site.baseurl}}//aa.png)
<center>This is the Transmitter Feather. As of for now, it is equipped with light sensors and temperature-humidity-pressure sensors. These sensors will pick up information around the surrounding.</center> 

![]({{site.baseurl}}//ff.png)
<center>The Transmitter Feather is equipped with Lithium battery and solar panel. The Solar Panel powers the feather and charge the battery during daytime, so that when night time comes, or during cloudy/rainy day, the feather can be powered by the battery.</center>

![]({{site.baseurl}}//Receiver%20Board%20Feather.png)

<center>This is the Receiver Feather. It will receive all the environmental data that the transmitters pick up in the surrounding.</center>

![]({{site.baseurl}}//Distance%20The%20Sensors%20Can%20Communicate%20with%20Obstacles.PNG)
<center>The two feathers can communicate with each other at the maximum of 226m if there are obstacles in the surrounding. This location is in Kapiolani Community College. </center>

![]({{site.baseurl}}//Distance%20The%20Sensors%20Can%20Communicate%20without%20Obstacles.PNG)
<center>The two feathers can communicate with each other at the maximum of 1.09km (or 0.6 miles) when there are no obstacles around. This location is in Kahala beach park. </center>

We now have a well-functioned prototype to demonstrate how the device works. If we get a chance to continue this project, we will develop a more user-friendly interface for the customers to read the information about their farms that the sensors pick up. Given enough resources and adequate skills, we would love to develop an artificial intelligent algorithms that can self-govern the whole farm, such as automatically provide extra water to the soil on very sunny day, release adequate fertilizers when the soil needs, identify early stages of harmful disease displayed in plants and warn the farmers.

