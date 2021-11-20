# Smart Planter

Smart Planter is planter pot that utilizes an inbuilt embedded system designed to endow a green thumb to anyone who grows their houseplant in it.

The soil is a special ecosystem dictated by soil conditions—like pH, moisture content, temperature, and organic matter availability—where the different soil organisms interact with the plants through its roots. Normally, all the organisms, even those that cause diseases or behave as pests, live in a balance with other species.
When any of the soil conditions are changed unfavourably, it can encourage the growth of one particular set of microflora or microfauna at the expense of others. If these are pests or pathogens, the attack on plants’ roots can be severe enough to affect its performance and yield. Good soil management is, therefore, one of the best ways to deal with soil diseases and pests.
The losses that soil pathogens and pests cause are partly because the causal organisms are working underground, out of sight, and are difficult to detect. By the time the symptoms appear in the above-ground aerial parts, the damage to the plant is substantial. There is also the danger that if the pathogens and pests are not contained they can spread and establish themselves in/on neighbouring plants and increase crop loss.
It is, therefore, crucial to detect incidence of pest and disease attacks as soon as possible.

**System Summary:**
The Smart Planter monitors the soil ecosystem inside the pot and root system of the plant that's potted in the same soil media. The planter achieves this by having an MCU interfaced with multiple sensors that maintain contact with the soil and a wireless backhaul that bidirectionally streams data to a server which enables the user to interact with the planter using an app. The planter has two power sources to choose from: solar or wired supply from a wall plug.

Before using the planter, the user enters the following in the app :

1. which plant they want to grow inside the pot
2. window facing directions
3. geographical location

This results in recommendations categorized as follows:

1. Type of soil, fertilizers and supplements, compost.
2. Amount of sunlight required for the plant
3. Temperature and humidity required for growth
4. watering cycle

The sensors used in the Smart Planter are all in contact with the soil matter using prong like structure that jut out from the inner planter wall into the soil. Their applications are given below:

1. **Temperature sensor**: measures the temperature of the soil at regular intervals of the day. User is notified if the temperature goes outside of optimum growth range.
2. **pH sensor**: measures the temperature of the soil at daily. User is notified if the pH goes outside of optimum growth range. Solutions are suggested to bring it back to normal.
3. **Dielectric Soil Moisture Sensors**: assess water content in soil by measuring the dielectric constant (an electrical property that changes depending on the amount of moisture present) in the soil. The relation between the measured property and soil moisture must be calibrated and may vary depending on environmental factors such as soil type, temperature, and salinity (electrical conductivity). Detects over watering.
4. **Piezoelectric Charge Accelerometer**: detect the pests/ insects through the sounds or vibrations they generate for communication or through noises that are produced incidentally during feeding and general movement. Sound/ Vibration Analysis is conducted on the recorded sounds. Notify user if any pest movement is identified.
5. **Gas Chromatographer - Mass Spectrometer**: Plants emit volatile organic compounds (VOCs) to promote growth, defense, and communication. So the VOCs they release in response to attacks by pests and pathogens will be different from that of a healthy plant. VOC profiling is done by using gas chromatography mass spectrometry (GC-MS). Use of VOC as biosensors is useful for early detection of infection before symptoms appear. If any disease is detected, user is notified.
6. **Root Imagers**: Detect root decay due to pests, pathogens or water logging by taking digital images of the entire root system. The images are analysed by firmware to calculate root dimensions and damage to roots and change in their architecture due to pest and pathogen attack. The root imager is implemented in the Smart Planter by having a transparent root-tube attached to the center of the base of the planter pot, reaching up halfway to the pot opening. The roots of the plants grow around the tube, and a scanner unit inside the root-tube takes images of the surrounding root system as frequently as is necessary. If any root decay is detected, the user is notified.

<p align="center">
<img src="https://user-images.githubusercontent.com/18359133/142734425-56e518c1-e162-4fd2-827e-c92a7caaaccd.png" width="800" height="800" border="10"/>
</p>



