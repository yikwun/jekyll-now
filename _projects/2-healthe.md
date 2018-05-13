---
layout: page
title: HEALTH-E
description: Android application for monitoring health
img: /images/thumbnails/t-healthe.jpg
---

The source code for the following project can be viewed [here](https://github.com/yikwun/HEALTH-E).
<br>
This project was completed in collaboration with Ali N. and Vincent Z. over the course of four months (May - August 2017).

## The Task

Utilize all phases of the Software Development Life Cycle to ultimately develop a mobile application that takes advantage of emerging technology in teams of 3-4. To effectively assess the project, four different checkpoints were arranged:
- Idea pitch
- Prototype demo
- Oral defence
- Final demo

### The Pitch

"As emerging technologies gradually conquer the digital era, the software that powers them become ever more important." HEALTH-E gracefully captures this notion as the seamless link between a smartphone and a corresponding smartwatch allows data to stream across the two devices effortlessly, making use of a smartwatch's heartbeat sensors to achieve consistent and accurate health monitoring at a significantly lower cost compared to competitors in the market. Storing crucial information about the user such as emergency contact, location, time, and recent history, HEALTH-E will accurately detect discrepancies in heart rate BPM and reliably contact emergency personnel in urgency. The pitch was presented to a class of around 50 students, one instructor, and two teaching assistants. The link to the full presentation file can be found [here]({{ site.baseurl }}/docs/presentation.pdf){:target="_blank" __}.

### Prototype

To collaborate most efficiently as a group, we decided to first complete modular components that required little to no cooperation/communication individually and implement the more complex features thereafter. My task was to implement the layout of the application while discrepancy sensing and smartwatch communication was entrusted to my team members to complete for the prototype checkpoint. At first, selecting a layout was simple as **Android Studio** provided the perfect setup for an application such as this. However, I also had to keep in mind all the features that were proposed for the project and consider the placements of each to make the application more intuitive to use.

#### Challenges

The first challenge I had encountered was what to have on the home screen. As the main purpose of the application was to monitor health using heart rate BPM data received from a smart watch, this number should be displayed to the user at all times. The options I had considered were:
- Display a single integer representing the BPM under a label
- Display a graph consisting of heart rate data and time
- Display the BPM on the smartwatch only

Ultimately, using a graph to display the data proved to be the most effective as it allows the user to have a sense of what their heart rate looks like over a period of time and easily locate the point of discrepancy should one occur. The problem with keeping only a single integer on the home page is that it does not display any trends that have been happening to the user. Displaying only on the smartwatch also limits the functionality of what actions can be accomplished on the smartwatch. A screenshot of the final layout is shown below.

![healthe]({{ site.baseurl }}/images/projects/health_e.png){: .center }
<div class="caption"> Note: Graph does not contain any data because no smartwatch was connected at the time this image was captured. </div>

### Oral Defence

This purpose of this checkpoint was to examine the progress of each group and explain the technologies and software architecture employed to create the project to the instructor and teaching assistants. During this walkthrough, we explained the MVP (Model-View-Presenter) and Singleton design patterns used in the project to overcome certain challenges we encountered. In particular, the MVP design pattern was employed to handle the interaction between the system and user while the Singleton design pattern solved the saving issue with the Model.

### Final Demo

After all the long hours of communication, writing code, and testing for bugs, HEALTH-E was finally complete. The entire list of features was demonstrated to the class and is listed below:
- Fall detection using height of device
- Automatic SMS and phone challenges
- Smart location using Google Maps API
- Record temperature and blood pressure
- Saves model inside storage
- Graphs user's heart rate using GraphView
- View history of previous records of incidents
- Smartwatch app runs as a service
- Vibration of device to discourage false positives of fall detection
- Heart attack discrepancy detection

## Reflection

Overall, the group project was a great learning experience in terms of collaborating with other people and the challenges of creating my first ever mobile application on Android with Android Wear. Utilizing open source projects such as [GraphView](http://www.android-graphview.org/){:target="_blank" __} definitely made it easier to visualize the data received from the smartwatch sensors. Furthermore, working with Android really tested my knowledge of Java while Android Studio made it really simple to design the layouts with its built-in emulator. Although challenges appeared along the way (one member got extremely sick towards the final demo checkpoint), I've learned to adapt to situations as they come despite the difficulties. All in all, this project widened my perspective on mobile development and made me realize that this is a field I am interested in pursuing.

Additional images of the finished project are shown below. <br> <br>

![healthe]({{ site.baseurl }}/images/projects/health_e2.png){: .center }
<div class="caption"> The initial screen after first opening the app prompting the user to enter their name. </div> <br>

![healthe]({{ site.baseurl }}/images/projects/health_e3.png){: .center }
<div class="caption"> Manual data input to store temperature and blood pressure - kept track in history and used for delivering to medical professional periodically. </div> <br>

![healthe]({{ site.baseurl }}/images/projects/health_e4.png){: .center }
<div class="caption"> Lists options for the user to edit user data, view history, and sync a smartwatch through Bluetooth. </div>

<br>
