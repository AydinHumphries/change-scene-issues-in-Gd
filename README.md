# Change Scene Issues in Godot 3d Networking Multiplayer Template

the original Facebook query:

"hello,

I'm having difficulties changing scenes in my Godot project when a player enters a collision area - I want the scene to change there to a user interface and change back to main screen when the player selects "return". the video below shows all the scenes, nodes and scripts but the most relevant parts are at 3m45s-5m30s and 6m30s until the end, pretty much (these parts show the code needed to interpret the patch). everything else before that shows remaining networking scripts that I used from the Godot template for networking a multiplayer game.

extra details:
I didn't want to remould the wheel on that code so left it pretty much the same and tried to work around it to create my own scenes from that rather than change it directly. however some of that code could be the reason that it's difficult to change scene which is why I showed some of it in the earlier parts of the video to be safe. additionally, it could be a logical issue - I would have coded "change scene when player enters collision area first time then when player returns to original scene do not change scene again until player leaves and then re-enters collision area". but instead it just has "change scene when player enters collision area" and "return scene when player selects return" because I don't know how to do that. 

if it's a logical issue, I can imagine the game engine would just ignore both of those commands to prevent some sort of stack overflow or internal logical looping mechanism that would cause the game to crash. but I don't know if it's to do with that.

full code: the project can be downloaded from AydinHumphries/change-scene-issues-in-Gd (github.com)

video: https://youtu.be/x7cP5ip_xxA"
