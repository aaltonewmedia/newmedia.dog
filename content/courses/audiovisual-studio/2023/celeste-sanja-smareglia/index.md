---
title: 'This is not an egg'
image: featured.jpg
hideImage: true
description: 'Audiovisual Studio'
summary: 'Audiovisual Studio'
type: 'courses'
authors: ['Celeste Sanja Smareglia']
bookCollapseSection: true
draft: false
---

{{<vimeo id="881432578" class="video">}}

## By Celeste Sanja Smareglia

- [Instagram @celestesanja](https://www.instagram.com/celestesanja/)

## Description

When a friend approached me to create interactive visuals for their band, I've always had a specific vision in mind. In this vision, eggs would fall gracefully in harmony with the song's rhythm.I chose the egg as a symbol due to its versatile metaphorical use, representing various circumstances from beauty to fragility. As the bands own intertextual lyrics and chaotic musical genre the egg represents its iconic self-irony, everything and nothing at the same time. Since I never had the time to bring this idea to life in Touchdesigner, I saw the Audio Video workshop as the perfect opportunity to start creating this visualization (at least its beginning). But at the end the egg is not forming a part of this visualization. This is not an egg. I instead crafted a retro and nostalgic backdrop that responds to mouse movements, contrasting with the falling metallic elements in the foreground. The whole visualization is breathing with the music and the person interacting; the metallic objects drop in time with the beat, particles change size with the rhythm, colorful noise shifts with the melody, and particles react to mouse movements, floating across the screen.

One of my goals was also to utilize the particle system but move away from the typical aesthetics that Touchdesigner typically offers. I wanted to incorporate simple 3D models into the scene and apply unconventional colors to the background. Simultaneously, I aimed to challenge myself by introducing different interactions into the visual aspect. I achieved this by creating three distinct 3D elements, each instanced within the same particle simulation. I could select which element to incorporate into the simulation based on keypresses, and these elements responded by altering their scale in time with the beat. After rendering the particles, I used a lookup node, which works almost as a filter, as it replaces the color of the rendered image with the color of the second input (in my case a displaced and animated circular color ramp which is also reacting to changes in the melody). The interesting patterns trailing behind each particle were achieved with a combination of the feedback and edge node. The particles react to the mouse movement; in simple terms, I used a metaball, guided by the mouse’s x and y coordinates, which generates a vortex force and then affects the already ongoing particle system. As a final touch, I added the metallic components, which fell in sync with the song's beat, instantiated along a basic line and spawned using a simple particle system, triggered by the beat's pulse.

The last touch were the metal parts, falling on the beat of the song. This was accomplished by placing them in succession along a simple line and activating them through a straightforward particle system, synchronized with the beat's pulse. After the workshop week, I decided to change the 3D model I initially imported from Quixel with one that I modeled for a recent project in Blender and then textured using Substance 3D Painter. Additionally, I decided to change the audio track with one more suitable to the visual scenery. One of the problems that I faced was the compression and video codecs, but I eventually managed to export the project in H.264 format using Adobe Media Encoder. I achieved the needed result by toggling parameters like bitrate, keyframe distance and SDR conform.

If I had more time, I would enhance the photorealism of the metal 3D model’s structure. I would as well change the animation, so that the model would rotate also around different axes (without that affecting the direction in which it falls), add more different models and then try to automate their random instancing.

## Resources and References

### Music

- ["Tu as de beaux yeux," created by Rrrrrose Azerty](https://loyaltyfreakmusic.com/music/x_x/)

### References

- [tutorial by elekktronaut](https://www.youtube.com/watch?v=hbZjgHSCAPI)

