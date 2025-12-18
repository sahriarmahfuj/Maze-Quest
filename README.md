Maze Quest:

Maze System
Procedurally generated maze on each run


All paths are guaranteed to be reachable


Exit is placed on the outer boundary of the maze


Clear visual distinction between corridors and walls


Maze design encourages exploration and navigation


Player Movement and Controls
W and S keys move the player forward and backward


Left and right arrow keys rotate the maze instead of the camera


Camera angle remains fixed during movement



Player has a physical collision size and cannot clip into walls


Camera System
Fixed-angle third-person camera by default


Camera positioned slightly above the maze for clarity


Top-down camera view toggle to see the full maze


First-person view toggle for immersive corridor navigation


Camera toggles do not affect gameplay logic



Combat System
Player starts with a fixed number of normal bullets such as 20


Normal bullets do not spawn in the maze


Normal bullets require two hits to defeat an enemy


Shooting direction is based on maze orientation



Temporary Power Items
Special power items spawn randomly in the maze


Power items have a limited active duration such as 15 seconds


Active power allows instant enemy elimination


Power effect is lost if time expires


Power items encourage time-based strategy



Enemies
Enemies spawn gradually over time


Enemies do not spawn near the player start or exit


Enemies stay idle until the player enters their line of sight


Alerted enemies chase the player through the maze


Enemy movement speed is slow and controlled


Enemies block corridors and restrict player movement



Treasure System
Treasures spawn randomly in reachable maze locations


Treasures can appear in dead ends or main paths


Collecting treasure increases the player score


Treasure system encourages full maze exploration



Game States and Progression
Player wins by reaching the exit boundary


Player loses when life reaches zero


Score tracks enemies defeated and treasures collected


Game can be restarted at any time to generate a new maze



Cheat and Debug Mode
Cheat mode can be toggled for testing


Cheat mode automatically solves the maze


Enemies are ignored while cheat mode is active


Used to verify maze generation and gameplay flow


