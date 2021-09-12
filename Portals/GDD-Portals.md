# Game Design Document - Portals 
Condensed portal game with smaller number of portals.

## Overview 
First-person game using environmental puzzles. Divided into single, unconnected levels.

### Gameplay 
The main aim of gameplay is to manipulate the surroundings in such a way as to unlock the exit. When the player completes the level, the game displays end-level text, and after a short delay, the player is teleporting to the next area. 

### Story
There is no direct narrative in the game. The only clues about the storyline the player can find in the environment or the general goal of the game (getting out from individual levels). 
  
### Target Platform: 
The target game platform will be Windows PC only. 
  
### Visual Style 
The environment in the game is supposed to resemble a sterile laboratory matching a place for testing dangerous objects or mechanisms. The light is uniform, full of cool colors. The only exceptions to this rule are objects that point the player to the way or those that draw the player's attention to something specific. 
  
### Audio Style 
The game should be devoid of music most of the time. The only sound the player can hear is from his footsteps or surrounding machines. 
  
### Game Menu 
The game menu is minimalistic - the player can only start a new game or select any level that has been completed. After the player is selecting a level, the player immediately starts the game. 
  
### Game Start
Although the game does not include a tutorial, the initial levels should show the player how to use the basic mechanics of the game based on simple puzzles. In the same way, the game introduces the player to new mechanics throughout the levels. 
  
After the level has started, the game starts counting down the time it will take for the player to pass the level. There are no penalties for ending a game slowly - it is only a motivation for the player to try to break his records.
  
After being hit by a trap, the player is spawning at the beginning of the level and time flies from zero seconds. Apart from that, there are no other penalties for losing a level. 

### In-Game HUD & Menus 
The HUD in the game is minimalistic. It only contains a brief description of the level's goal (reaching the exit) with the countdown time. When the player ends the level, description and countdown disappear, and in their place, appear congratulations for completing the level, along with the time the player managed to reach. 
  
### Main Menu 
The game menu with all the fonts should be strict and devoid of ornaments and colors. 

## Gameplay Details

### Level Selection
After completing a level, the player can repeat it at any time from the main menu. The game is saving only the best time of each level.

### Full Level List
Although the levels are played one after the other, they are arranged according to a pattern - first, the player plays a not very complex
level to teach him a new mechanic, then the player is forced to use the new mechanics in connection with the previous ones to achieve his goal. In the new level, the player has to look at the new mechanics from different angles - for example, a player who has learned to use cubes to activate buttons, quickly has to learn that the same cubes allow you to climb higher platforms.

Later stages also force the player to creatively combine all the previously learned mechanics with a new one on a new level.

### Mechanics
There are many types of obstacles in the game that kill the player's character. In addition to such obstacles as lasers or missiles, the player may encounter automatic cannons that track his position, or dangerous surfaces (spikes or, for example, lava).

The player character can catch the cubes placed on different levels. Although the cubes look similar, some of them have additional visible properties - for example, some shoot a laser beam, others can manipulate gravity. The player must use these cubes to make their way to the exit. However, that such a cube can kill the player if the laser of the cube touches the player's character.

### Controls
The player controls the character using the WASD buttons, with the mouse using to turn around. Interacting with objects is done by pressing the left mouse button.

### Winning The Level and Game
The player wins the level when he reaches the end-level object -  rotating purple cube. The game is complete when the player has passed all the levels. If the player wants, he can return to any level even after completing the game. Although the time it takes to complete a challenge depends on how you choose to complete it, it shouldn't take an average player more than 5 minutes to complete a level.

### Score
The game adds times from all completed levels. This time is adjusted if the player manages to pass any level with a better time.

### Challenges
Every few levels, the complexity of the new one will be slightly harder. This level forces the player to use the mechanics he learned during the previous ones. These levels should be longer than the previous ones - completing them should be a test of skill and knowledge of the game mechanics for the player.