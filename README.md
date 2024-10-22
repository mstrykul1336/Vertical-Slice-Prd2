# Vertical-Slice-Prd2
Vertical Slice Prd2 of Shadows Over Suburbia. 
**Play:**
**Link to Full Project:**
**Credits:**
First Person Controller: https://assetstore.unity.com/packages/3d/characters/modular-first-person-controller-189884?srsltid=AfmBOorWmRFs9bx7ebwFwd15ni4eQk7cPH1-OeGcAaLAW0HUaVO0Xw5H
ChatGPT for questions and bugs, learning how to do certain things I haven't done before in Unity.
Canva for demo asset icons (I will be drawing some of them later) 
Fantasy Forest Village: https://assetstore.unity.com/packages/3d/environments/fantasy/fantasy-forest-village-123484
Polygon City Pack: 
https://assetstore.unity.com/packages/3d/polygon-city-pack-environment-and-interior-free-101685
Farland Skies:
https://assetstore.unity.com/packages/2d/textures-materials/sky/farland-skies-cloudy-crown-60004
Fantasy Terrain Textures: 
https://assetstore.unity.com/packages/2d/textures-materials/free-fantasy-terrain-textures-233640
Fantasy Towns Music Pack: 
https://chrislsound.itch.io/fantasy-towns-music-pack

**10/21/24:**
**What was done:**

**To Do:**
Add in abilities for the rest of the roles that get them:  
Detective: Investigation (watch one player at night to see what happens to them) 
Assistant: Connections (discover if a target player attacks anyone tonight) 
Clairvoyant: Psychic (can select two players to learn if they are friendly or enemies to each other, based on helpful or destructive) 
Old man: Voter Fraud (can vote twice instead of once) 
Villagers: Attack (can attack people for ¼ heart) 
Add in UI for attacks so you know that you were attacked or taken or healed, whatever happened to you. 
Make the shield work as intended and actually block an attack at night (it should block poison, bleed, and normal attacks) 
Bug check the knife to make sure it properly attacks players, attacks player in the dropdown provided.  
I believe it does, but make sure the inventory actually takes the item out when it is used.  
Make a cool UI (image or video, but WEBGL hates videos) for when players die (randomly show different versions of the UI of them dying, like minecraft changes the text). Maybe change this to animation loaded elsewhere with the player’s model and a random death scene.  
Make the voting UI better and cleaner.  
Clean up the player list UI.  
Add in a font that matches the aesthetic for all text in the game.
**Backlog:**
Add in destructive and helpful versions of these abilities:   
Mayor: (currently has mayor's basement for helpful, but if destructive, you will be able to sacrifice the player to WiggleBlorp) 
Assistant (destructive would get brainwash, where you send an anonymous message to a player to invite them to the cult (destructive) side).  
Detective (destructive would get unlawful investigation, same investigation but you get the option to attack them, causing them to bleed for 1/4 hearts DOT for 3 nights) 
Medic (currently has heal, would need fake heal for destructive where it makes another player believe they were attacked and then healed) 
Everyone else gets the same ability no matter what side. 
Add in passives to two characters: Medic (immune to poison and bleed) & Clairvoyant (can't die at night, needs to be voted out). I need to make it so it doesn't give away their characters to any players though, just doesn't end up working if you attack them. 
- I want to try to make it so instead of disconnecting players, they can spectate as ghosts, but can't interact. I think this should work out as long as in all my loops that go through player list, I also check if the player is not dead before adding them to whatever.
- And add in that button to toggle player movement or not.

