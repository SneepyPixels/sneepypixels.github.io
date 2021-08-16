## Devlog
### Tentative To Do List:
|Area | Tasks|
------------ | -------------
Area 1 | Elevator Button Panel
|| Front Desk Furniture models|
|| Wall Decor
|| Bathroom Textures
|| Bathroom objects (sink, toilet, etc.)
|| Bathroom mirror(?)
|| Introductory TV(?)
|| Front Door)
Area 2 | * Surface texture
|| Surface texture
|| Lighting
|| Cohensive level design

### Notes

##### 8/16/2021

Narrative
 - Scaled down scope of narrative

Player script changes:
 - Player slope handling added (Custom stop-on-slope)
 - Re-adjusted floor collision/floor normal detection (Ray casts, added debug display)
 - Re-adjusted body collision (Scaling values, local position)
 - Re-adjusted crouch functionality (Ceiling detection, collision body translations)

Environments
 - Added low-ceiling testing mesh
 - New area in progress

##### 8/11/2021

Conceptualized a general idea for an 3D First Person type of game where you can play from two perspectives.
Someone who volunteers themself as a willing participant and someone who is doing a normal day-to-day play test.
Over course of 1.5 weeks, I was able to model a small "waiting room area" with bare minimal features:
  - Player is able to move, look around, crouch, and interact with specific objects 
  - Player makes dynamic sfx depending on floor surface ~~and movement speed~~
  - Created interactables to trigger sound effects
  - Meshes (mostly) have textures
  - Lighting set-up and baked
  - Skybox placeholder
  
