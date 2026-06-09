# 👾 **DroneCombatPrototype**
The goal of this project was to create a set of Blueprint classes that can be easily integrated into any prepared level. The project includes enemy drones that engage a player-controlled drone. Enemy drones are capable of detecting and targeting the player, moving toward their position, and firing projectiles.

Each drone has a configurable health value and is destroyed once it receives a specified amount of damage. Two drone variants are provided: a regular drone and a boss drone. Key gameplay parameters, including movement speed, attack rate, health, and other combat-related attributes, can be easily adjusted through exposed Blueprint variables, allowing for quick balancing and customization without modifying the underlying logic.

## ⚙️ Features
* Blueprint class '**BP_Drone**' - an enemy drone which is capable of aiming at the player, move in its direction and shoot laser projectiles
* Blueprint class '**BP_DroneBoss**' - stronger enemy type, shoots faster, has more health than regular Drone
* Blueprint class '**BP_BlasterBeam**' - handles behaviour of projectiles, spawning Niagara Systems at collisions etc.
* Blueprint class '**BP_BotPawn**' - drone which can be controlled by the Player, has its own health points, upon receiving lethal amount is destroyed and game needs to be restarted
* Blueprint class '**BP_BotSpawner**' - upon passing through the designated box collision, enemies will spawn at the marked target points,  developer can choose whether to spawn a regular **BP_Drone** or a **BP_DroneBoss**, as the Spawn Actor Class variable is **Instance Editable**
  

## 🕹️ Controls
* W - Move Forward
* S - Move Backward
* D - Move to right
* A - Move to left
* Spacebar - Move Up
* LCTRL - Move Down
* Left Mouse Button - Shoot
* F - Rapid Fire 

# 🧠 What I Learned
* Creation of **Intermediate** Blueprint Classes
* Creation of Pawn Blueprint from ground up
* Preparing **Input Mapping Context** and **Input Actions** for the Pawn Blueprint
* Idea of Blueprint instances
* Using **Line Traces**
* Adding crosshair via **Widget Blueprint**
* Basic functionality of **Blueprint Interface**
* Basic functionality of **Meta Sounds**
* Creating and edditing **Niagara Systems**

## 📈 Future Improvements
* Visible health bars could be added for both the player and enemy drones
* Health pickups could be added to restore the player’s health

## 🎬 Gameplay Preview
https://github.com/user-attachments/assets/48681030-0134-4599-b3f3-c82531d23178
###
https://github.com/user-attachments/assets/fcf78599-2256-4c87-85c8-c0b0645218c5
## 🛠️ Blueprints

# BP_BotSpawner
<img width="1908" height="1024" alt="Image" src="https://github.com/user-attachments/assets/03dac6e4-0ec6-47c3-94bb-d9461fc9035e" />

# BP_Drone
<img width="1915" height="1029" alt="Image" src="https://github.com/user-attachments/assets/ca28b033-cecb-43e0-bb06-f505e01a0583" />

### BP_Drone video preview
https://github.com/user-attachments/assets/1cffde82-84c3-4b68-b4bb-1eb3be358e41

# BP_BotPawn
<img width="1915" height="1027" alt="Image" src="https://github.com/user-attachments/assets/44bc2748-7b1c-442b-998d-9ac7849c776a" />

### Input Mapping Context
<img width="2554" height="1387" alt="Image" src="https://github.com/user-attachments/assets/71440b37-4380-4e03-8f8f-7485aba18259" />

### Adding Input Mapping Context and Crosshair widget
<img width="1917" height="1029" alt="Image" src="https://github.com/user-attachments/assets/1e627991-bfa6-4f55-8c86-8c8ebdaf2f39" />




