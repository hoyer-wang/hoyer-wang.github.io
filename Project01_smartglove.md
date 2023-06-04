<h3>Smart Glove System in Mixed Reality Scenarios</h3>

<p style="text-align:justify">Numerous students were forced to take online classes from home during the COVID-19 pandemic. The challenge is that many harmful and only practicable offline chemical or biological experiments are challenging to carry out in a domestic setting. Fortunately, the advent of mixed reality technology has made it possible to overcome the time and physical limitations of laboratory instruction and has given students an efficient way to carry out safe experimental exercises. As a result, the primary contribution of this work is to develop the MRLab, a mixed reality smart experiment system, which enables the input of sensor information, speech information, and scene visual information. Simultaneous, this study also develops a multimodal hybrid fusion model called GVVS based on the input data in order to determine the user's experimental intention. The user can make use of experimental instruments or drugs in the real world while also interacting with objects in the virtual world and observing the associated experimental phenomena.</p>

<img src="/assets/img/mrsg01.png">

<p style="text-align:justify">This study creates a smart glove with multi-sensor fusion for the use case of secondary school experiments. The glove, which mainly consists of STC microcontroller, sensor set and binocular camera, can collect multi-sensor signals and scene information from the user, and then analyze the user's gesture movements and the experimental objects they want to operate. </p>

1. The microcontroller is the central control module used for handling the sensor signals.

2. The sensor set comprises of a vibration sensor, flex sensor, pressure sensor, and posture sensor (MPU 6050).

   - <p style="text-align:justify">The smart glove's flex sensor, which is found in the finger section, measures the degree of the user's finger bending situation and maps those changes to the virtual hand in the Unity scene.</p>

   - <p style="text-align:justify">The smart glove's MPU 6050, which is found on the back of the hand, is used to measure the user's hand's three-axis angle, angular velocity, and acceleration.</p>

   - <p style="text-align:justify">The smart glove's finger belly has a pressure sensor that measures the condition of finger use while operating an experiment.</p>

   - <p style="text-align:justify">The smart glove's vibration sensor, which provides the user with vibration feedback of the contact process and heightens the sensation of a genuine user experience, is situated in the back of the hand.</p>

3. <p style="text-align:justify">The binocular camera is fixed in the wrist portion of the smart glove, which not only allows for real-time information gathering about the experimental scene, but also addresses the issues with obscuration and poor long-distance object recognition accuracy. It is frequently brought on by the traditional virtual experiment practice of using cameras and KINECT devices. The smart glove's binocular camera and sensor group transfer sensing data and visual data to the computer through Bluetooth and USB, respectively. Figure 3 illustrates the hardware structure of this system.</p>

<img src="/assets/img/mrsg03.png">
