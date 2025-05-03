# Project-06-3DRPG
## Features Added
Includes a user-controlled third-person 3D player: The third-person 3D player can be controlled by A, W, S, D (Movement), Space(Jump), and Left-Shift(Running).

The camera follows the movement of the player: The camera is always following the Player.

The player's model is animated: I have added the "Firing Rifle" animation from Mixamo.com. (Although I did not add any shooting effect, just a pose)

Includes at least one AI agent: There are two types of AI agents: NPC and Rats. The NPC will just stand there and always look at the Player. I also added a small canvas on the NPC and a text says: "Hi, Adventurer!" For the rats, I added the nav mesh surface all over the planes. And I add a RandomMovement C# script on the rats which allows them to move randomly.

Includes a dialogue conversation with an agent: When the player is getting close to the NPC, and the player is facing towards the NPC, there will be an "F" icon that shows up, which tells the player how to have a conversation with the NPC to get the quest.

Reports the player's score: The player will increase their score when colliding with rats. The initial score for each rat is 1000. But it will decrease over time, which means that the faster the player catches rats, the higher the score they will get.

The game includes terrain and/or obstacles: I have used ProBuilder to create some walls and an arch.

The game includes a hand-held weapon with which the player can influence the world: I only added a feature that the player can not have the shooting animation before they have collided (picked up) the Weapon in the map. But the weapon does not do anything, because I found that it is hard to let the player shoot in a certain direction. In third-person view, the camera (where we really see) does not stay in the same direction will the player's (the character's) facing direction. Also, the "firing rifle" has a weird pose where the gun is pointing towards the sky, not the front of the player.

The game has a clear objective: After the player catches all the rats, they win.

## References to resources used in the project
Materials: https://freepbr.com/

Gun Model & Rat Model: https://free3d.com/

Character/Animation: https://www.mixamo.com/

## Created by
Franklin Pu
