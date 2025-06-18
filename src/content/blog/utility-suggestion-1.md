---
title: 'Utility suggestion based on map position on CS2 #1'
description: 'Lorem ipsum dolor sit amet'
pubDate: 'Jul 17 2025'
---

### Context of the project

In a short resume, Counter-strike is a game 5x5, and the main goal as a terrorist is dominate the bomb, plant the bomb and explode. As a counter-terrorist, you have to defend the bombsite and defuse the bomb.
For example in Inferno map, when you try to dominate the bombsite B, you need to throw the smokes in CT and Coffins. 

And how you gonna do that? **You need to learn the spot of the smoke**.

![Coffins smoke](https://i.imgur.com/FK7zIqW.gif)

As you can see you need to stop in the **right place and aim in the right pixel** to get your smoke successfully.

### The project

The main goal of this project is a webcam who will aim the CS2 radar, based on my position on the map, the application will sugest smokes, molotovs and flashes based on my position in the map.

My first step was explain in details for ChatGPT, and he suggests possible tools who gonna help me to build the application. Note that I didn't ask for a done code, just a suggestion to which path I need to go.

His suggestions was something that I already knew, who is the [OpenCV](https://opencv.org/), based in computation vision, application web in [React](https://react.dev/) and [Websocket](https://socket.io/pt-br/) to have feedbacks in real time, and a specific term for something we probably will use, called "template matching".

> Template matching is a technique in image processing used to find portions of an input image (a larger image or target image) that matches a template image (reference image or smaller image). 

Probably we gonna use that to get a image X who gonna be the image of the radar, and image Y who gonna be the radar of my game. With all that, I can define keypoints in some parts of the radar, and if I get closer of this keypoint, he gonna suggest utilities. Something like this:

![Radar](https://i.imgur.com/cljn6Zq.png)






