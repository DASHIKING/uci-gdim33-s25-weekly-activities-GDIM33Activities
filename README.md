# GDIM 33 In-Class Activities
## W1
### Activity 1
[Google Paint1](https://docs.google.com/drawings/d/122QOKK0hZIUno_Q0jJ_vcVixD7VN3SM41nLzGfHJDic/edit)
   
1. I chose the card battle type of games, where players fight against NPCs and eventually defeat them. Players can use different cards to perform various actions, such as attacking, defending, etc. I was interested in games like Slay the Spire and Clash Royale and referred to them.
 
2. My tablemate chose a game similar to Left 4 Dead 2, which is about fighting zombies. The similarity between us is that we both chose games where we fight against NPCs, and we both have a dark style.
   
3. LA also enjoys this card-based battle game. He likes this type of game that relies on clear strategies. This is similar to me.


### Activity 2
<img width="1024" height="566" alt="image" src="https://github.com/user-attachments/assets/cc249cb5-abac-4998-96aa-c28d15058f6c" />



## W3
### Activity 1
<img width="1440" height="1652" alt="image" src="https://github.com/user-attachments/assets/6a55fe2e-7407-4de9-bdcd-28b93bb08569" />


### Activity 2

 1. This way, multiple different objects (such as walruses, penguins or other NPCs) can conveniently share the same "signal". If I want to modify the name of this event in the future, I only need to change it once in the Variables panel, without having to manually modify it in each Graph. This makes the code cleaner and reduces the possibility of errors.

 2. When I clicked on the walrus but the dialog box didn't pop up, Debug.Log helped me identify where the problem was. I added a Log after the click event on the walrus. If the information was displayed in the Console, it indicated that the click detection was fine, and the problem might be in the state machine transitions. It's like a "signpost", telling the code where it is in the execution process.

 3. Yes. In my Vertical Slice 3D or interactive games, when players are exploring, I need to lock the mouse (Locked) to control the perspective; but when players open menus or dialog boxes, I must release the mouse (None) otherwise players won't be able to click the UI buttons. Controlling the state of the mouse well can greatly enhance the gaming experience.

 4. Very relevant. My game also needs to distinguish different modes, such as "combat mode", "exploration mode", or "pause mode". Using game states (Game State) enables the game to run different logic at different stages (for example, pausing enemy movement during dialogue), which makes the overall logic management of the project very clear.


## W4
### Activity 1

1. My playable build now includes movement using the WASD keys, and there is also a flashlight function. Players can use the flashlight to see the scene in front of them clearly. I also designed the environment of the game, which consisted of a room with a floor, a ceiling and several walls. Players can move around inside and use the flashlight to observe the corridors and rooms. My playtesting goals are to figure out what I need to do next and how I should modify my game environment.

2. OKADA Naoma, Thomas Sun, Beiduo Jin

3. The environment is a bit giddy. The lighting is too dim. It should be adjust later. In addition, more rooms can be added.

### Activity 2

1. Under the current system settings, writers can easily add more dialogues without writing any code. This is because all the dialogue content, response options, and the logic for their transitions are stored in a ScriptableObject (i.e., the DialogueNodeW4 file). Writers only need to create a new file in the Unity editor by right-clicking, and inputting text and dragging connections between different nodes as if filling out a form. The system can automatically recognize and generate new content based on the logic we have written.

2. There are no strict limitations. As long as the computer's memory and hard disk space are sufficient, the writer can create hundreds or even thousands of nodes to build a vast story network. The only actual limitation might come from the UI level, where buttons might extend beyond the screen boundaries. However, this is a limitation in visual design rather than a limitation of the dialogue system itself.

3. The "Regenerate Nodes" button functions much like a "mirror" for Visual Scripting, allowing it to re-scan all the code within the project. This is because when you add new variables (such as visual effect prefabs) in the C# script, the Visual Scripting node library does not automatically update in real-time. By clicking this button, the system is forced to refresh the node list, converting the changes we made in the code into searchable and usable visual nodes.

4. <img width="775" height="467" alt="image" src="https://github.com/user-attachments/assets/ccd60248-f648-47c3-b4aa-6d2657880f64" />

