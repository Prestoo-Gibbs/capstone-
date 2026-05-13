Miner Game
An arcade mining adventure where you dig through planets, collect resources, and upgrade your drill as you go deeper.

Objective
Dig downward through planetary layers, collect valuable resources, and reach the core of each planet to progress to the next world.

How to Play:

Move with LEFT/RIGHT

Jump with UP

Mine blocks with SPACE

Press C to change your miner colors

Press S to open the upgrade shop

Press R to reset the current planet


Mineable Materials

Dirt — easy to mine, common near the surface

Stone — basic rock, moderately durable

Coal — common mineral, gives moderate credits

Iron — valuable metal, worth more points

Gold — rare mineral, high reward

Water — found on the water planet

Lava — found on hot planets

Ice — found on ice planets

Bedrock — unbreakable core material

Planet Types:

Hot planets: only lava, iron, gold, and bedrock below the surface
Water planet: mostly dirt and water
Ice planets: icy crystal terrain with water and stone mixes

Upgrades:

Better Drill — mine faster with each level
Deeper Drill — reach lower rows deeper into the planet
Speed Boots — move more quickly underground and on the surface

Class Overview:

MinerGame.java
Game entry point. Creates the main window and starts the menu and game panel.

GamePanel.java
Main engine and renderer. Handles the game loop, input, camera, tile drawing, and planet backgrounds.

Tile.java
One block in the world. Tracks type, durability, and break logic.

TileType.java
Defines all block materials, colors, durability, and values.

Player.java
Handles miner movement, jumping, mining, and player appearance.

TerrainGenerator.java
Generates procedural planet terrain and applies planet-specific block rules.

GameLevel.java
Manages progression, depth tracking, and upgrade state.

Planet.java
Represents each planet instance with a deterministic seed and spawn-cleared starting area.

WorldManager.java
Controls planet progression and stores created planets.

Particle.java
Handles visual mining particles and fade-out effects.

HUD.java
Draws the UI overlays: status, inventory, upgrades, and depth.

Upgrade.java
Stores upgrade data, cost scaling, and current level.

ChunkManager.java
Loads and unloads procedural world chunks for infinite terrain.

DevelopmentTimeline.java
Documents the development timeline and estimated hours.

Project Files:

MinerGame.java — game entry point and main menu

GamePanel.java — update loop, rendering, input, and camera

Tile.java — block durability and break logic

TileType.java — all block materials and values

Player.java — miner movement and mining behavior

TerrainGenerator.java — procedural planet terrain generation

GameLevel.java — progression, depth, and upgrade state

Planet.java — planet instance data and spawn clearing

WorldManager.java — planet progression manager
Particle.java — mining particle effects
HUD.java — on-screen UI
Upgrade.java — upgrade cost and level rules
ChunkManager.java — procedural chunk loading/unloading
DevelopmentTimeline.java — development timeline documentation
Happy mining!
