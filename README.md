# CAP4720_vanderzalm

CAP4720 - Computer Graphics (Fall 2021)
* Project Link: https://observablehq.com/@bvanderzalm/cap4720-fzero-finalproject

## About the course
This course will cover the fundamentals of interactive 3D Computer Graphics and 3D graphics programming. Students will learn graphics programming using `WebGL2` (OpenGL ES3.0), and `Javascript`. We will use `TWGL`, a simple library that is designed to make WebGL programming compact. This course will cover Vector Algebra and Transformations that are at the foundation of 3D graphics.


Given below is a list of topics to be covered during the course. The order in which the topics will be covered may not be the same as the order in the list.
* Math for Computer Graphics: Vector algebra, Coordinate System
* Graphics Systems, Graphics Pipeline
* WebGL graphics API, Shader Programming
* Programming in WebGL2, the class will use TWGL, a helper library designed to make using the WebGL API less verbose.
* Transformations, Camera and Viewing
* Material, Lighting, and Texture Mapping
* Data structures in Computer Graphics
* Interaction and Animation

## Project Description
F-Zero is a single player racing game set in the far future where the cars have no wheels and hover, steering more like an airplane using vectored thrust and rutters that interact with the air than like a car which uses contact forces between the ground and the tires. The first game released in 1990 in Japan, and 1991 in North America and was made in order to showcase a faux-3D effect of the Super NES named Mode 7. This technique is somewhat similar to the cubemap skyboxes we have made before and allows for making a 3D background using 2D assets, which will be crucial to making a 3D game in a month without a game engine. The project we are proposing is to recreate and update the original F-Zero with 3D models replacing many of the 2D sprites the original game used.

**My Contribution (Additional Lighting):**
 My contribution involved implementing a night time mode where I kept track of the car’s position where if it entered a particular area a lighting effect would appear on the car’s model. A lighting effect was also applied on the spectators. I also helped determine if the car was located inside the green pit zone where I triggered the UFO to come down and then gave the car additional lighting with a green specular color to give it a green reflection from the UFO’s green light beam. 
 
 As you go along the track (during night mode) you’ll notice the lighting on the car change to simulate passing lamp posts, if there was additional time and/or additional members of the team I would put futuristic lamp posts next to these areas to give the true effect. NOTE: the default mode is daytime and the lighting effects are only present in the night mode. Please click the checkbox below the gl canvas to enable night time.
 
 This was done using diffuse, specular, and ambient lighting on the car and spectators during night mode, this is primarily based on the car's location.
 
 For more information on the rest of the group's contributions please refer to the Final Report pdf.

**Project Link:** https://observablehq.com/@bvanderzalm/cap4720-fzero-finalproject


**Project Demos**:

Demo going into detail on my contributions: https://youtu.be/g76afunjtfA

Short 16 second demo showing my contributions: https://youtu.be/CpvbRfkPmVs
