Dayana Ramirez
IT266 section 001
==========================


SET UP
======================

clone github repository

git clone [url]

cd quake2-FinalProject

Then go into  visual studio and open quake2.sln

Build the mode in Release mode

look for the .dll ex: game/release/gamex86.dll


copy the mod files(.dll, .cfg,...) and place them in a folder where the game exacutable resides for me it was:

steam/steamapps/common/Quake2/[modname folder]


create a shortcut of the original quake2.exe

right click on the shortcut and go into properties

from there enter in the target section and type:

"C:.../..../steam/steamapps/common/Quake2/quake2.exe" +set game [modname]

Mod can now be opened but the config.cfg file where it binds the keys was not working for me so i
bind the keys using the terminal inside the game

When player is in the game weather in single player or multiplayer doesnt matter

access the terminal by pressing ~

type the following to bind keys for the new movement to work

bind SHIFT dash

bind MOUSE2 dodge

bind e punch

bind f stomp

GamePlay
=============================================================

listen to the metronome to stay on beat there will be also a visual indicator how fast the pace will be

player can fire, jump, stomp, dash, double jump, punch, dodge to hit the 'note'

if player stays on beat player will be given one of the 5 power up where as a physical item or given automaticaly im not sure yet:
        1.slowdown tempo
        2.stronger bullets
        3.freeze enemies
        4.multi bullets
        5.

There will also enhancements and hinderance when player is off beat or on beat
        1.speed up sound
        2.silence
        3.hit window increase ( player has .25 seconds to hit the beat)
        4.blast enemies back

weapons will be adjusted to be able to fire to the beat

