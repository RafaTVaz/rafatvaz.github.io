---
layout: post
title: SnowGlobe
date: 2021-02-15 13:20 +0100
categories: [Games, GameJam]
tags: [gamedev]     # TAG names should always be lowercase
image: 
  path: ..\..\assets\img\pics\VR-CoverPic.png
  #lqip: data:image/webp;base64,UklGRpoAAABXRUJQVlA4WAoAAAAQAAAADwAABwAAQUxQSDIAAAARL0AmbZurmr57yyIiqE8oiG0bejIYEQTgqiDA9vqnsUSI6H+oAERp2HZ65qP/VIAWAFZQOCBCAAAA8AEAnQEqEAAIAAVAfCWkAALp8sF8rgRgAP7o9FDvMCkMde9PK7euH5M1m6VWoDXf2FkP3BqV0ZYbO6NA/VFIAAAA
  #alt: Preview Image
---

**SnowGlobe Technique for VR** is a first-person VR project done for a VR semester course at Uni. 
<!-- #![Pic](https://img.itch.zone/aW1nLzg1OTc5MTMucG5n/original/qBYs2L.png) -->


Experimental Semester Group Project for better object interaction in VR; Chose multiple objects from afar and manipulate them in the palm of your hands. Move objects in your hands and they move in real space too.

<!-- *The game is available on [itch](https://bahble.itch.io/push-the-pull)* -->

### The Project
This was the final group project for a semester course about **Virtual and Augmented Reality**. Made by a group of 4 students. The challenge was to pick one or a couple of papers on VR/AR and develop them a bit. 

The work was based on two selection techniques presented in the paper [Exploring the Effects of Environment Density and Target Visibility on Object Selection in 3D Virtual Environments](https://ieeexplore.ieee.org/document/4142854). The paper attempted to solve problems with object selection in dense and/or far environments. We tried to solve the same problem with a different approach that also made it easier to access objects that aren't visible or are mostly obstructed. It's also possible, through this technique, to interact with objects scattered around the scene without pulling them toward the player or necessitating the player to move to the objects. 

The technique is to use a **globe or bubble** that spawns in the hand. This globe can change size to 'grab' more things and be moved along a ray shot from one of the hands. The globe encapsulates multiple objects and then *clones* these onto the palm of the player's hand.  The player is then able to interact with these clones freely while the real objects move the same way.


### My contribution 


The specific work I did on the game was:
- Initial idea
- Lead designer
- Programming




### Showcase:
{% include embed/youtube.html id='UZ9I-63Tcv0' %}