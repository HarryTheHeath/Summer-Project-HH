# 2022 Forsbergs Skola Summer Project 
![An Island Away](https://user-images.githubusercontent.com/90158105/183082412-39aaf688-a9d6-4b6c-8f4d-884e08cbff1c.png)

**An Island Away** is a 5-week-long project I undertook to create a 3D platformer in UE5.

[Pitch Document](https://docs.google.com/document/d/19fuJum10Y-G-NkFuVgQg-aVFYC2eE7numAVVrhllVbo/edit?usp=sharing)

## Overview

This is a 3D Platforming experience inspired by classic games of the ["Collect-A-Thon"](https://en.wikipedia.org/wiki/Platform_game#:~:text=format%2C%20and%20the-,%22collect%2Da%2Dthon,-%22%20genre%20began%20to) subgenre, such as Banjo-Kazooie. This namely meant implementing collectible items that trigger bouncy UI triggers and creating a 3D character with several platforming movement abilities that feel satisfying to control.

As I've never developed from scratch in UE5, I saw this assignment as an opportunity to better get to grips with the engine and the blueprint system and decided that it was most important to have mechanics in place than to have much game design beyond a starting demo area. This decision was also made in part due to a planned collaboration falling apart. However, I'm satisfied with the amount of unique features I've been able to develop and the different areas of discipline I've applied myself towards while solo-developing, with a definite clear secondary focus on technical art and animation.

## Shipped Features

### Quests & Interactions
- Interactable NPCs with Quest and Multi-Choice Dialogue capabilities
- Collection and Target Location Quests
- Unlocks to new areas and for mew abilities based on Collection Progress
- Coin & Key Collectibles with animations, sounds, and adaptive UI
- Readable Signs & Directional Posts
- Progress Tracking for Quests and Collectables
- Wider Player Interaction System (Press E)


### Movement & Abilities
- Locomotion Animation States: Idle -> Sneaking -> Walking -> Sprinting
- Double Jump locked behing a progress event
- Stamina System with UI Depletion Bar and Movement Exhaustion Penalty
- Boat Pawn Possession and control, with complete buoyancy in the water
- Spectator Camera Mode (Press P)

### Engine Creations
- World Design, Landscaping, Foliage Painting, Water Body Creation
- Pixelated Post-Processing Camera Effects
- Camera Transitions when entering Dialogue or Possessing Pawns
- Responsive UI with Animations for Coins, the Stamina Bar, and Collectibles
- Actors with Physics Simulation features such as buoyant objects
- Animation Retargeting
- Integration of a wide range of Assets

# Scenery
![Buildings](https://user-images.githubusercontent.com/90158105/183080902-a0149d2b-1f25-4d19-b66c-0ccf3c13e472.png)

# Quest Completion Event 1
![Quest unlock](https://user-images.githubusercontent.com/90158105/183080950-454f242c-202f-49f4-a72a-f246986b964c.png)

# Quest Completion Event 2
![Quest complete](https://user-images.githubusercontent.com/90158105/183080937-78bd5bdc-b63e-431d-9118-08ccc081c5a8.png)

# Driving The Boat
![Boat](https://user-images.githubusercontent.com/90158105/183081503-7f6fb860-58c8-43f5-9633-141acf14236e.png)

# Night visuals
![Starry Night 1](https://user-images.githubusercontent.com/90158105/183080977-1906180b-6f0e-4bb4-896f-7649bbedabf0.png)

# Stamina Drain
![Stamina](https://user-images.githubusercontent.com/90158105/183081004-39494e08-e88c-43f4-8bfa-07424598e881.png)

# Buoyancy and Water Physics
![Floating](https://user-images.githubusercontent.com/90158105/183081493-99090ed9-1b14-4cc5-8d86-a5876cc88c7e.png)

# Initial Base Landscaping
![Capture2](https://user-images.githubusercontent.com/90158105/183081693-788b88a3-19de-4776-a720-b8928fcebc4c.JPG)
