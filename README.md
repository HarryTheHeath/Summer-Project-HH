# 2022 Forsbergs Skola Summer Project 
![An Island Away Thumbnail](https://user-images.githubusercontent.com/90158105/183003287-321d121b-b4fe-4199-8220-c83fd307df28.png)

**An Island Away** is a 5-week-long project I undertook to create a 3D platformer in UE5.

[Pitch Document](https://docs.google.com/document/d/19fuJum10Y-G-NkFuVgQg-aVFYC2eE7numAVVrhllVbo/edit?usp=sharing)

## Overview

This is a 3D Platforming experience inspired by classic games of the ["Collect-A-Thon"](https://en.wikipedia.org/wiki/Platform_game#:~:text=format%2C%20and%20the-,%22collect%2Da%2Dthon,-%22%20genre%20began%20to) subgenre, such as Banjo-Kazooie. This namely meant implementing collectible items that trigger bouncy UI triggers and creating a 3D character with several platforming movement abilities that feel satisfying to control.

As I've never developed from scratch in UE5, I saw this assignment as an opportunity to better get to grips with the engine and the blueprint system and decided that it was most important to have mechanics in place than to have much game design beyond a starting demo area. This decision was also made in part due to a planned collaboration falling apart. However, I'm satisfied with the amount of unique features I've been able to develop and the different areas of discipline I've applied myself towards while solo-developing, with a definite clear secondary focus on technical art and animation.

## Shipped Features

# Quests & Interactions
- Interactable NPCs with Quest and Multi-Choice Dialogue capabilities
- Collection and Target Location Quests
- Unlocks to new areas and for mew abilities based on Collection Progress
- Coin & Key Collectibles with animations, sounds, and adaptive UI
- Readable Signs & Directional Posts
- Progress Tracking for Quests and Collectables
- Wider Player Interaction System (Press E)


# Movement & Abilities
- Locomotion Animation States: Idle -> Sneaking -> Walking -> Sprinting
- Double Jump locked behing a progress event
- Stamina System with UI Depletion Bar and Movement Exhaustion Penalty
- Boat Pawn Possession and control, with complete buoyancy in the water
- Spectator Camera Mode (Press P)

# Engine Creations
- World Design, Landscaping, Foliage Painting, Water Body Creation
- Pixelated Post-Processing Camera Effects
- Camera Transitions when entering Dialogue or Possessing Pawns
- Responsive UI with Animations for Coins, the Stamina Bar, and Collectibles
- Actors with Physics Simulation features such as buoyant objects
- Animation Retargeting
- Integration of a wide range of Assets
