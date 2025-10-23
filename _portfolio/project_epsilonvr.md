---
title: "Epsilon VR"
layout: single
author_profile: true
excerpt: "framework, player application, and content creation tool for developing and deploying procedure based training on desktop and VR."
header:
  teaser: /assets/images/bio-photo.jpg
gallery:
  - url: EpsilonVRPanel.jpg
    image_path: /_portfolio/epsilonvr/EpsilonVRPanel.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"


---

Target: Windows, Touch, VR  
Software:  Unity, Visual Studio, C#

EpsilonVR is a framework, player application, and content creation tool for developing and deploying procedure based training on desktop and VR. 

{% include gallery caption="This is a sample gallery with **Markdown support**." %}


## Products created with EpsilonVR

U.S. Navy: Auxiliary Propulsion System course, Surface Steering Gear course, Virginia Payload Tube procedure

TrainPoint: Lockout Tagout procedure, L'Oreal procedure, Hazardous identification procedure , Trenching and excavation procedure  

## Main Features

- Single standalone exe for both desktop and VR.
- Content can be developed by artists with no scripting by using the procedure development tools built on top of the Unity editor by building lists of Steps, Action Lists, Actions, and Interactions.
- Platform abstraction allows most interactions to be developed in the content once and work in all navigation modes and VR.
- Desktop support for different navigation modes and run-time hot-swapping between orbit, first person, and fixed camera modes.
- Desktop support for Keyboard and mouse, Xbox controller, and touch screen
- Framework is built to dlls and packaged into a UnityPackage that can be imported into a fresh project to create new content.
- Export content as a file collection from the content project which can be loaded into the player.
- Share assets between exported content to reduce file size
- Basic multiplayer support

## Framework Technologies

Unity, StrangeIOC, MVCS, Dependency Injection, VRTK, UFPS, Photon, Unit testing, Jenkins CI, Automated builds, Test reports, Gitlab