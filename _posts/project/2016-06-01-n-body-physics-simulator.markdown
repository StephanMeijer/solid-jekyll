---
layout: project
title:  "N-Body Physics Simulator"
categories:
- project
img: nbps.jpg
thumb: nbps.jpg
carousel:
- single03.jpg
website: https://github.com/N-BodyPhysicsSimulator/Main
tools: Python 3, WebGL, Pixi.JS, NumPy
periode: Midden 2016 - heden
---

#### N-Body Physics Simulator

Op het moment ben ik bezig met een N-Body Physics simulator in Python 3. Deze simulator bouw ik als profielwerkstuk voor mijn opleiding. Een N-Body Physics simulator is een simulator die zwaartekracht op verschillende (hemel-)lichamen berekent. De berekeningen doen we in Python, en de visualisatie van de berekeningen gaan we doen met webtechnologie waarbij we gebruik maken van WebGL en de library PixiJS.

We gebruiken libraries zoals NumPy (voor berekeningen met vectoren) en zijn van plan ArrayFire te gaan gebruiken (met ArrayFire spreken we de GPU aan voor berekeningen in plaats van de CPU, ArrayFire spreekt op zijn beurt weer CUDA en OpenCL aan).
Het eindresultaat moet er uit gaan zien [zoals hier te zien.](https://www.youtube.com/watch?v=qKp1M4T6z24)

Momenteel testen we de Simulator door middel van doctests, maar we willen de simulator uitgebreid gaan testen.