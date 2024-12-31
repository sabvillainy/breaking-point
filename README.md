# Breaking Point

Breaking Point is a fast-paced, top-down shooter game built using Unreal Engine 5. This project was developed as part of a game design and Unreal Engine course. The game combines intense combat mechanics with a dark, mission-driven narrative where players take on the role of a mercenary completing high-stakes missions.

## Features
- **Gameplay Mechanics**: 
  - Mission-focused levels with enemy clearing objectives.
  - Bullet-time mechanic for strategic combat.
  - Dynamic enemy AI with melee and ranged attack patterns.
- **Level Design**: 
  - Oda-based progression within multi-level structures like mansions.
  - Players must clear all enemies in each room to progress.
- **Boss Fights**: 
  - Unique bosses, each inspired by animal masks (e.g., Rabbit, Crow, Snake, Wolf), with distinct combat styles.
- **Music and Audio Design**:
  - Fast-paced metal tracks during gameplay, ambient sounds for menus and cutscenes.
  - High-quality sound effects, including bullet impacts, enemy screams, and dynamic audio changes in bullet-time.

## Prototype Video
Curious to see the gameplay in action? Check out the prototype gameplay video on YouTube:

[![Breaking Point Prototype Video](https://img.youtube.com/vi/U7aoPdhANvs/0.jpg)](https://www.youtube.com/watch?v=U7aoPdhANvs)

## Prototyping Mechanics

The following mechanics are implemented in the current prototype of the game:

### Main Menu
- A **Main Menu** is available, featuring:
  - **Start Game**: Begins the gameplay.
  - **Quit Game**: Exits the application.
  - The **Game Title** displayed prominently.

### Movement and Actions
- **WASD Movement**: The player can move using the `W`, `A`, `S`, and `D` keys instead of the default top-down template's mouse-based movement system.
- **Dodge Roll**: The player can perform a dodge roll to evade attacks or reposition quickly.
- **Reload Mechanic**: The weapon has an 8-bullet magazine, requiring the player to reload once it is empty.

### Bullet Time Mechanic
- A **Bullet Time** mechanic has been implemented, allowing the player to slow down time temporarily, adding a strategic element to combat.

### Enemy AI
- **Melee Enemies**:
  - Actively seek out the player once they are in their line of sight.
  - Attempt to attack the player with melee punches upon approach.
- **Weaponed Enemies**:
  - Engage the player with ranged attacks upon spotting them.
  - Two types of weaponed enemies:
    - **Pistol Enemies**: Fire at the same speed as the player.
    - **Rifle Enemies**: Fire at a faster rate than pistol enemies.

### Death Menu
- When the player dies, a **Death Menu** appears:
  - Displays a "You Died!" message.
  - Includes buttons to **Retry** or return to the **Main Menu**.



## Project Status
This is a **prototype** and not a complete game. The project demonstrates core gameplay mechanics, level progression, and enemy behavior. While fully playable, additional polishing and features would be necessary for a full release.

## Repository Note
Due to GitHub's file size limitations, some larger project files and directories (e.g., `DerivedDataCache`, `Intermediate`, `Saved`) are not included in this repository. These files are not essential for understanding the code or core functionality, as Unreal Engine can regenerate them. However, for a complete project setup, please download the full project files from the following link:

**[Google Drive - Full Project Files](https://drive.google.com/file/d/1x_aXFAHI1rF2xVxelXKVE_NTxo2Vh40y/view?usp=sharing)**


## Getting Started
To run this project:
1. Clone this repository to your local machine. or download the full project files from the Google Drive link above.
2. Open the `.uproject` file in Unreal Engine 5.

### Requirements
- Unreal Engine 5.4

## Contributing
As this is a student project, contributions are not being accepted at the moment. Feel free to explore, give feedback, or fork the repository for your own experiments.

---

Thank you for exploring Breaking Point! If you have any questions or feedback, feel free to reach out.
