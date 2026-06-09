# 👾 **DroneCombatPrototype**
## During this project 

## ⚙️ Features
* Blueprint class '**BP_Drone**' - an enemy drone which is capable of aiming at the player, move in its direction and shoot laser projectiles
* Blueprint class '**BP_DroneBoss**' - stronger enemy type, shoots faster, has more health than regular Drone
* Blueprint class '**BP_BlasterBeam**' - handles behaviour of projectiles, spawning Niagra systems at collisions etc.
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

## 🛠️ The Process

# 🧠 What I Learned
* 

## 📈 Future Improvements
* Visible health bars could be added for both the player and enemy drones
* Health pickups could be added to restore the player’s health

## 🎬 Gameplay Preview
https://github.com/user-attachments/assets/48681030-0134-4599-b3f3-c82531d23178
###
https://github.com/user-attachments/assets/fcf78599-2256-4c87-85c8-c0b0645218c5
## 🖥️ Screenshots
BP_BotSpawner
<img width="1908" height="1024" alt="Image" src="https://github.com/user-attachments/assets/03dac6e4-0ec6-47c3-94bb-d9461fc9035e" />

