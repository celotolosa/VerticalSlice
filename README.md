# GDIM33 Vertical Slice
## Milestone 1 Devlog

My visual script graph, specifically movement uses the transform translate node in an update cicrcuit. The data comes from the Horizontal and Vertical input axes, which is then created into a vector 3 and multiplied by an object variable named "speed" (initially set to value). This is then plugged into the translation port and the player moves relative to self.

<img width="2000" height="2500" alt="unnamed" src="https://github.com/user-attachments/assets/c2dba161-b42d-43c1-9419-44140bd8f3fa" />
This is my new state machine system break down. It is not what my final state graph machine will be, but it is the current system that I am using for movement in my game + the state machine itself. It works by updating a UI text based on the player movement and whether they are idle or moving/waking. I want my system to relate to other systems in the game lik npc dialogue, and being able to talk to an npc whether they are moving or not, and adding a state machine for talking to an npc, e.g: activeDialogue, notTalking, etc. 

## Milestone 2 Devlog

1. Create 8 directional movement animations using a human 8 directional movement asset
   1. Create a new blend state tree
   2. Use 2D directional movement
   3. Use 8 different animation clips
      - Forward
      - Backward
      - Forward right
      - Forward left
      - Backward left
      - Backward right
      - Left
      - Right
   4. Incorporate into Visual Scripting Graph

2. NPC Dialogue
   1. Two NPC's
      - one NPC will be the NAVmesh agent where they will locate the player, and give the first quest when accepted
      - This quest will direct the player to find the second NPC and continue to finish another quest
    2. Create ENUM's for the NPC script to differentiate which NPC the player is talking to
    3. Create nodes for the dialogue that will hold replies and npc lines
    4. Create AdvanceDialogue() method, and call it when the player is within a certain distance and the player clicks

3. Create full map with cave and terrain
   1. Import assets into Unity
   2. Setup terrain using the asset's materials and layers
   3. Build cave with route to a new NPC

After Coding:

1. I think that the breakdown really did help in coding my game to the next requirements. I followed it in a bit of a different order, (3, 1, 2), but the order didn't matter as much since the process for each was different. I would improve my breakdowns a little more in the future if I were to do them again by adding examples of the steps from previous activities, or add tutorial links
2. In C# and visual scripting I've used both animations and movement that are bridged together. 
3. The unity system I want graded is the Scriptable objects that I used for NPC dialogue. It my intended and used unity system that I also pitched.

## Milestone 3 Devlog
Milestone 3 Devlog goes here.
## Milestone 4 Devlog
Milestone 4 Devlog goes here.
## Final Devlog
Final Devlog goes here.
## Open-source assets
- Cite any external assets used here!
