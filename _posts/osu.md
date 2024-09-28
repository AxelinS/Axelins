---
layout: post
title: AI that plays Osu!
description: AI, Tensorflow, Keras, Pytorch, Python. 
image: assets/images/Osu-Logo-PNG_004.png.jpg
---

## AI that plays Osu!
I started creating this artificial intelligence at the end of August 2023 and it currently has 99% aim accuracy at almost any level. 
This was trained using several recorded replays and synchronizing the video with the coordinates and click that occurred in each video frame.

When searching for sources I found that OpenAI had managed to make an AI that plays Minecraft work using a technique called video pretraining, this inspired me to try this method with my model that plays Osu!.
This technique worked phenomenally in the aiming of the model, although in the clicking part it still failed a lot.

Although I originally started the project with Tensorflow and managed to achieve good results, I decided to also learn a little about Pytorch and in the end I made a faster and more accurate version than the one I had in Tensorflow.

I am currently perfecting the clicking part with deep Q learning to increase the consistency with which I click just in time to obtain the best score.

### Operation
To start the AI ​​I simply open Osu! and I run a python script which starts taking screenshots of the game all the time, the screenshots are saved in sequence of 6 inside a tensor which is sent in a pipe to the part in charge of inference. 
When I enter a game I only activate the loop that is responsible for the inferences and outputs such as the coordinates [x,y], I process them and using ctypes the cursor moves to the coordinates.
With the click part it is simple, only from the output the probability of the click is identified and based on this the "x" key is pressed to give the equivalent of the click in the game.

### My experience
This was my first project related to artificial intelligence and when I started creating it I discovered that it is an area that I really like and I am excited to learn much more.
I learned and went through many learning stages doing this project, I learned from how to make a simple basic model of an input, a hidden layer and an output to do a simple conversion from fahrenheit to celsius to an image recognition model and a detection model. of objects just to be able to understand the bases to carry out this, my first project.

I have been going through difficulties for several months and solving the problems I encountered, learning from scratch to create artificial intelligence. Since this was my first project, it took me a long time to get results that met my expectations (That AI could beat a human).

I tried different techniques and architectures for the model by doing a lot of tests leaving the model training for days. 

I could say that thanks to this project I discovered my passion for artificial intelligence.

### Equipment specs
Ryzen 5 5500

RTX 3060 12GB

32GB RAM DDR4 3666MHz

Windows 11

* <a href="https://clips.twitch.tv/ProudDignifiedDonkeyStrawBeary-DJJ4h0AaHFeaybmi">Aim video</a>
