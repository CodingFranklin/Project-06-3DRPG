# Project-06-3DRPG
## Features Added
**Includes a user-controlled third-person 3D player**: The third-person 3D player can be controlled using **W, A, S, D** (movement), **Space** (jump), and **Left Shift** (run).

**The camera follows the movement of the player**: The camera smoothly follows the player at all times.

**The player's model is animated**: The "Firing Rifle" animation from Mixamo.com is applied. *(Note: No actual shooting effect is included—only the pose.)*

**Includes at least one AI agent**: There are two types of AI agents: **NPC** and **Rats**.  
- The NPC remains stationary and constantly looks at the player. A small canvas is attached to the NPC showing the message: *"Hi, Adventurer!"*  
- Rats move randomly using a custom `RandomMovement` C# script and a NavMesh surface applied across the ground.

**Includes a dialogue conversation with an agent**: When the player is close to the NPC **and** facing them, an **"F" icon** appears, indicating that a conversation can be triggered to receive a quest.

**Reports the player's score**: The player gains score by colliding with rats. Each rat starts with **1000 points**, which decrease over time—encouraging quick action for maximum score.

**The game includes terrain and/or obstacles**: Custom walls and an arch were created using **ProBuilder**.

**The game includes a hand-held weapon with which the player can influence the world**: The player cannot trigger the shooting animation until they pick up the weapon in the scene.  
> However, the weapon does not perform any action. Implementing shooting direction proved challenging due to the third-person perspective—the camera does not always align with the character’s facing direction. Additionally, the "Firing Rifle" animation points the gun upwards rather than forward.

**The game has a clear objective**: Catch all the rats to win the game.

## References to resources used in the project
- **Materials**: https://freepbr.com/  
- **Gun Model & Rat Model**: https://free3d.com/  
- **Character/Animation**: https://www.mixamo.com/

## Created by
Franklin Pu
