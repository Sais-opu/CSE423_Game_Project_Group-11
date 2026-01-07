# 3D Treasure Collector

3D Treasure Collector is a simple 3D game where the player explores the world, collects treasures, avoids falling obstacles, and uses special power-ups to survive. The goal is to collect treasures while managing health and time.

---

## Team Members

- Simran Zaman Mayabi  
- Md Saidul Islam Apu  
- Al-Amin Sagor  

---

## Languages and Technologies Used

This project is built using:

### Python
The entire game logic is implemented in Python.

### PyOpenGL
Used to render 3D graphics and handle drawing:

- `OpenGL.GL` for rendering shapes and objects
- `OpenGL.GLU` for camera and projection utilities
- `OpenGL.GLUT` for window handling and simple 3D primitives

Other Python modules used:

- `math` for calculations
- `random` for treasure and obstacle placement
- `time` for timers, countdowns, and power-up durations

The project does not use a game engine. All mechanics are implemented manually using OpenGL.

---

## Game Overview

The player moves around a 3D world, collecting normal and special treasures. Some treasures require a key. Random bricks fall from above, reducing health when hit. Special treasures provide temporary advantages such as extra time and health boosts.

---

## Features

### Player Movement
Players can freely move around the 3D environment, navigate obstacles, and reach treasures.

### Treasures
- Normal treasures increase score.
- Special treasures require a key and give additional benefits for 5 seconds.
- Collecting treasure plus eating a special treasure gives 3 total points.

### Key Mechanic
Special treasure can only be opened using a key.  
Sometimes players must jump or move through tricky paths to reach it.

### Health System
Random bricks may fall from the ceiling.  
If the player is hit, health decreases.

### Time System
Collecting a special treasure increases remaining time by 5 seconds.

### Power-Ups
Special treasures improve health and temporarily reduce danger.

### Ceiling Collapse
Random bricks fall as the player explores. Avoiding them is essential to survive.

---

## Cheat Mode

Cheat Mode allows the player to see only the key and normal treasures while obstacles go down.  
When a special treasure is collected in cheat mode, brick falling stops for 5 seconds.

---

## Win / Lose Conditions

### Win
- Collect the required treasures  
- Stay alive until the end  
- Keep enough health and time to finish  

### Lose
- Health reaches zero  
- Time runs out  
- Hit by falling obstacles too many times  

---

## Restart

Players can restart the game after losing or winning and try again.

---

## Suggested Controls (adjust if different)

- W / A / S / D – Move  
- Space – Jump  
- E – Interact / Collect  
- R – Restart  
- C – Toggle Cheat Mode  

---

## Summary

3D Treasure Collector focuses on timing, survival, and exploration.  
Use the key wisely, avoid falling bricks, collect treasures, and stay alive long enough to win.

---

