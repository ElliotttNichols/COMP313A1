# COMP313A1
First Unreal Test

Author: Elliott Nichols (300316315)

COMP313 Assignment 1 Submission

YouTube project link: https://youtu.be/Ek_DzfG_gWc

Game Name: Elliott's Brian Test Game

Game Description and summary: 
  This game is a basic first person shooter where the player can roam the map and shoot randomly spawned Brians, who will move about the map. These Brians currently have 
  a built in path to travel but have been set up to be able to randomly roam the map as well as follow the player. When shot the player recieves 10 points and at 50 
  points the game is ended. While the current game is extremely basic the goal was to have the spawned NPC's be somewhat randomized and to have them all have different 
  behaviours. The goal being some AI's would act 'suspiciously' and killing them would reward points while others should be ignored or points taken away. This was left
  out due to time.
  
  The most difficult part of the entire project was setting up an AI for pathfinding and spawning. Because the AI's were spawned by the spawner and not initial level
  actors I found it difficult to reference them in the ways suggested by most tutorials. There were also a lot of extra components to getting an AI to move, such as a
  bounding box to tell them where they can go (There was a stage where I spent an hour trying to fix my targt points only to realize they were an inch outside of this
  box). The animation transitions were a little difficuly to get working and I can see many issues ahead should I choose more complicated transitions.
  
  I found the most intresting feature that I included was the height mapping and terrain generation. Because my computer runs slowly I had to remove all the 4k textures
  I originally included and I also disabled a lot of the advanced lighting I set up to increase performance. I am looking forward to creating a more visually stunning
  version of this game with a map looking the way I initially wanted.
  
  Overall I am not happy with my final output, but am very happy with what I learned on the journey to creating it. I hit a LOT of roadblocks in getting Unreal basics 
  to work but I now feel quite confident with the blueprints system and feel familiar with the c++ coding side of Unreal. I am hoping to spend a majority of the break 
  learning more and really flexing what I have learned with this project.
  
Features from brief that were not included due to time:
  -Restart Level
  -Slider function in menus
  -c++ coded blueprint (The online tutorial created object was not used in the final game).
