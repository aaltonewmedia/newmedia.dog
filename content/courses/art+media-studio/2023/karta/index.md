---
title: 'Karta'
date: '2023-06'
draft: false
image: img/karta.png
description: 'Procedural workflows and tools for visual authoring are increasing in popularity. Once a designer or artist gets past the learning curve of one such tool, it becomes easy to iterate on ideas and create variations. Karta is my own twist on this paradigm, an attempt to shift the focus away from isolated, singular files and towards inter-connectivity and composition from disparate parts.'
summary: 'Karta is designed for making maps of everything that exists on an artists computer. It should therefore be thought of as something like an augmented file browser, an intermediate layer between specialised applications.'
categories: ''
tags: ['art+media studio', 'interactive and immersive art']
authors: ['Viktor Teodosin']
type: 'projects'
---

Procedural workflows and tools for visual authoring are increasing in popularity. Once a designer or artist gets past the learning curve of one such tool, it becomes easy to iterate on ideas and create variations. Karta is my own twist on this paradigm, an attempt to shift the focus away from isolated, singular files and towards inter-connectivity and composition from disparate parts. It is designed for making maps of everything that exists on an artists computer. It should therefore be thought of as something like an augmented file browser, an intermediate layer between specialised applications. What exists now is a proof of concept for this vision, with a few central features simply implemented. 

Karta started as a custom note-taking and visual organisation tool. Its main differentiating feature was the focus on local graphs, and being able to organise the same notes in varying arrangements depending on context. It eventually occurred to me to experiment with ways to use the application for creative coding. The current iteration of it is a simple state machine; a tool for arranging visual compositions and traveling between them, transforming smoothly from one to another. 

<video controls width=100%>
  <source src ="./video/karta.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

Compositions are defined as scenes with child nodes that represent the content of those scenes. Scenes may also be connected to other scenes. The currently active scene has its contents output to the background of the node graph. The user may choose an adjacent scene to transition to, and they will see the contents smoothly animate in the background. 

The concrete implementation in this version is just rectangles moving to different positions and scaling. But the intuitive direction from here is to extend this system to cover different shapes and eventually 3D models. The edges between states are logical places to store keyframed animation data, for more custom transitions. Animating like this may be more flexible than defining keyframes in a linear timeline. It's a different kind of structure, more restrictive than playing video clips from a library, but also more authored and detailed, like linear animation.  Interactivity with the final animation becomes possible, and therefore live performance. The artist would define compositions and transitions in advance, and then improvise when traveling through those connections. This prototype is quite a distance away from realising such a vision. But from the experiments and thinking I've done on this topic, it seems a dedicated application would be worth making. 


