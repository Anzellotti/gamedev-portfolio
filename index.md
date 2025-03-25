---
title: Giovanni Anzellotti - Gamedev Portfolio
---
# **Finished Games**

>## **Onigiri**

- Top-down physics-based action game
- First gamedev experience
- Developed on Unity
- **Winner of the Cotoletta d'Oro (first place) at [Cotoletta 8-bit](https://www.cotoletta8bit.it/)**

This game was developed for the Videogame Design and Programming course at Polimi from October 2023 to January 2024. It was developed by a team of five students, and I took on the role of team leader, lead designer and programmer.\
The goal of the course was to develop a vertical slice of a game with a duration of 20 minutes.\
The game received the maximum grade of 30L from the course. We got a third place at Unimi's NGD 2024, and a first place at the first edition of Cotoletta 8-bit.

Check it out **[>>here<<](https://polimi-game-collective.itch.io/onigiri)**.

|![]({{ "/resources/onigiri_enemies.gif" | relative_url }})|![]({{ "/resources/onigiri_boss.gif" | relative_url }})|
|![]({{ "/resources/onigiri_arcade.gif" | relative_url }})|![]({{ "/resources/onigiri_cotoletta.png" | relative_url }})|

|![]({{ "/resources/toa_starters.png" | relative_url }})|![]({{ "/resources/toa_altar.png" | relative_url }})|
|![]({{ "/resources/toa_relics.png" | relative_url }})|![]({{ "/resources/toa_hooh.png" | relative_url }})|

>## **Build-a-Bearration**

- Top-down bullet heaven
- Customizable player character
- Developed on Unity

I developed this game for the Acerola Game Jam 0, a two-week game jam with a maximum team size of 1, in March 2024.\
The game features a flexible character builder that allows for a lot of wonky combinations.

Check it out **[>>here<<](https://joevanni.itch.io/aberration)**.

|![]({{ "/resources/aberration_assembly.gif" | relative_url }})|![]({{ "/resources/aberration_builds.gif" | relative_url }})|

---
# **In development**

>## **PVP (Plane VS Plane)**

- Online pvp plane combat
- Networked Physics simulation
- Developed on Unreal Engine 5

The development of this game started as a way to learn Unreal Engine, as well as a way to improve in some areas I felt I was lacking in, namely 3D and online. The development started in September 2024, but is currently on hiatus as I focus on my master thesis.\
The game utilizes the new Networked Physics system, which allows for a seamless experience when controlling the physics-driven plane while maintaining the authority of the centralized dedicated server.

|![]({{ "/resources/plane_shoot.gif" | relative_url }})|

>## **Turn-Based Prototype**

- Turn-based combat
- Flexible buff/debuff system
- Minimax enemy AI
- Entire battle logic written in C#

A prototype for a turn-based battle system I'd like to expand on in the future. It was written in a couple of weeks in June 2024.\
The most interesting aspect of this project is the fact that all of the battle logic is written in pure C#, with all Unity-specific logic such as monobehaviours decoupled by using observers and callbacks. This allowed me to easily implement a very flexible enemy AI that utilizes minimax tree search to select optimal moves.

|![]({{ "/resources/turnbased_block.gif" | relative_url }})|

---

# **Gamedev-adjacent projects**

>## **Dungeon Mesh**

- Very basic game engine
- Entity-component-system architecture
- Built-in scene editor
- Written in C++, using Vulkan for rendering and GLFW to handle window and input

This project was developed over a couple of weeks for the Computer Graphics course at Politecnico di Milano, in a group with two other students.\
I personally handled the engine side of the project, from the loading of the scene from disk to the entity-component-system architecture, as well as some lower-level aspects with some Vulkan calls to correctly render the scene, and some shader logic.\
We received the maximum grade of 30L.

|![]({{ "/resources/dungeonmesh_environment.gif" | relative_url }})|![]({{ "/resources/dungeonmesh_editor.gif" | relative_url }})|

>## **AR application for medical training**

- Master thesis project at Polimi
- Simulator for complex surgical operations
- Developed on Unity 6, for the Meta Quest 3S headset

Currently still in development, this project is my master thesis project, developed under Professor Marco Gribaudo, with the assistance of PhD student Marco Domenico Buttiglione.\
The application uses the XR Interaction Toolkit package to provide a physics-based simulation of two surgical operations (thoracoscopy and laparoscopy) in an AR environment, in order to aid the training of future surgeons.\
A large focus of the development is to offer a platform-agnostic set of tools to be used in further development by future theses.\
While the research part is still ongoing, the application received positive feedback by a group of thoracoscopy surgeons.

[This section will be updated in the future with some footage and the final evaluation.]