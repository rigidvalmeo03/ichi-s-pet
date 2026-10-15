ichi-s-pet

A tiny pixel-art desktop cat that walks around, takes occasional breaks, plays with a fish, and creates floating hearts when clicked.

Try It Out:
https://rigid-valmeo.itch.io/ichi-pet
Use this itch.io link.
https://drive.google.com/drive/folders/1NoEqFkjwDh62bx1itReNcD_lHAuQKG_t?usp=sharing
Watch this video to see the cat in action.
Move the cat around, pet(click) it to see hearts float up, and drag the fish towards the cat to be eaten.

QUICK START
I. Play the Game
1. Download the game from the [itch.io page](YOUR-ITCH-IO-LINK).
2. Extract the downloaded ZIP file.
3. Open the game executable to start playing.

II. Run from Godot
1. Install [Godot Engine 4](https://godotengine.org/).
2. Download or clone this repository.
3. Open Godot's Project Manager and import the project by selecting its "project.godot" file.
4. Open the project and run the main scene.

Features:
- Walking Cat Animation: Moves around the game window.
- Idle Animations: Occasionally pauses walking and plays an idle animation.
- Floating Hearts: Clicking the cat spawns three hearts that float upward and disappear.
- Interactive Fish: Drag the fish toward the cat to make it disappear temporarily before returning after five seconds.
- Movable Window: Drag the cat to move the game window around your screen.

Built With:
- Godot Engine 4: Game engine.
- GDScript: Scripting language.
- 2D Sprites and Animations: Cat, fish, and heart pixel art visuals.

How It Works:
IchiPett uses Godot's "Node2D" and "AnimatedSprite2D" nodes to control the cat's movement and animations. Its GDScript handles movement around the game window, randomly timed idle checks, mouse clicks, and dragging interactions.

The floating hearts are separate scene instances. When the cat is clicked, the game creates three hearts, each of which moves upward and removes itself after a short lifetime. The fish interaction uses a timer to make the fish reappear after it has been given to the cat.

Project Structure
IchiPett/
├── addons/
├── cat/
│   ├── idlecat.png
│   └── walk.png
├── hearts/
├── fish.png
├── heart.gd
├── heart.tscn
├── heart_new.tscn
├── ichipett.gd
├── icon.svg
├── node_2d.tscn
├── export_presets.cfg
└── README.md

Credits:
Created as a personal project while learning Godot 4 and GDScript.
All artwork, sprites, animations, and game assets were created by me using Ibis Paint X.
Built with Godot Engine
