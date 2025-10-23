---
title: "Epsilon VR"
layout: single
author_profile: true
classes: wide
excerpt: "framework, player application, and content creation tool for developing and deploying procedure based training on desktop and VR."
header:
  teaser: /assets/images/bio-photo.jpg
gallery_editor:
  - url: /assets/images/epsilonvr/epsilonvr-panel.jpg
    image_path: /assets/images/epsilonvr/epsilonvr-panel-th.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/epsilonvr/epsilonvr-step.jpg
    image_path: /assets/images/epsilonvr/epsilonvr-step-th.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
gallery_game:
  - url: EpsilonVRPanel.jpg
    image_path: /assets/images/epsilonvr/EpsilonVROrbit_mode.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: EpsilonVRPanel.jpg
    image_path: /assets/images/epsilonvr/EpsilonVR_VR_mode.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: EpsilonVRPanel.jpg
    image_path: /assets/images/epsilonvr/EpsilonVRFirstPerson_mode.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"


---

Target: Windows, Touch, VR  
Software:  Unity, Visual Studio, C#

EpsilonVR is a framework, player application, and content creation tool for developing and deploying procedure based training on desktop and VR. 

{% include gallery id="gallery_editor" caption="This is a sample gallery with **Markdown support**." %}

{% include gallery id="gallery_game" caption="This is a sample gallery with **Markdown support**." %}


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