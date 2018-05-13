---
layout: page
title: User Interfaces (4 Projects)
description: A variety of projects demonstrating different layouts and interactions
img: /images/thumbnails/t-ui.jpg
---

To view the source code for all projects listed below, please visit [here](https://github.com/yikwun/User-Interfaces).

## Games, Drawing, Manipulation, and Media (Overview)
An introductory course for user interfaces, CS 349 provided many opportunities to explore and implement different layouts ranging from classic games like Snake to unique interfaces for existing platforms like YouTube. The goals for each of the projects are as follows:
- Build an interactive game using C++ and learn how to handle real-time 2D animation
- Utilize MVC (Model-View-Controller), widget library, layout manager, and 2D graphics
- Direct manipulation using 2D graphics
- Incorporate real-world external APIs into interactive and responsive applications with dynamic layouts

### Snake

A classic game originating in 1976 from Blockade is re-envisioned on the XWindows System, written in C++.

![snake]({{ site.baseurl }}/images/projects/snake.png){: .center }
<div class="caption"> Snake looking for food, running on XQuartz - an X11 system for MacOS. </div>

When your score reaches 20, a new level begins and the speed at which the snake travels is increased. Can you reach a high score of "Level 5"?

### Doodle

Drawing has never been more exquisite until the addition of animated undo and redo. Watch your drawing seamlessly undraw itself at the press of a button!

![doodle]({{ site.baseurl }}/images/projects/doodle.gif){: .center }
<div class="caption"> A demonstration of the drawing and animated undo-ing capabilities. </div>

Complimented with a customizable colour palette, your ability to create intricate and elegant illustrations is only enhanced. What can you make with this new sketcher?

### Paper Dolls

A humanoid figure is interesting in the ways its body parts can be manipulated. The upper arms (shoulders) can rotate a full 360° while lower arms (elbows) only 135°; why is that?

![paper_dolls]({{ site.baseurl }}/images/projects/paper-dolls.png){: .center }
<div class="caption"> The paper doll in an interesting pose with its head tilted, arms and legs bent, and floating in the center of the screen. </div>

Explore the limits of what the paper doll can do in this experimental and interactive application! What is a position the paper doll can be in that you can't?

### YouTube GUI (Graphical User Interface)

YouTube is widely known as a leader in the video sharing platform with over five billion videos watched every day. I have created an application that can save your favourite videos from a search on YouTube, while also providing a functionality to rate videos locally. Ultimately, a collection of all your favourite videos are compiled into one place which can be accessed instantly! The following images were created using the search query "cat".

![youtube1]({{ site.baseurl }}/images/projects/youtube01.png){: .center }
<div class="caption"> The graph view of the YouTube application. Resizing the window will dynamically change the number of videos displayed on each row, with queries being limited to 25 results. </div>


![youtube2]({{ site.baseurl }}/images/projects/youtube02.png){: .center }
<div class="caption"> The list view of the YouTube application. Switching between the two views will not reset any ratings already assigned to any given video. </div>


![youtube3]({{ site.baseurl }}/images/projects/youtube03.png){: .center }
<div class="caption"> The list view showing how the filter works when applied to the search results. In this case, only videos with a rating of two or more stars are displayed. </div>

<br>
