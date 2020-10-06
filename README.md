# Hades Boons - Python GUI

The game [Hades from Supergiant Games](https://store.steampowered.com/app/1145360/Hades/ "Hades on Steam") is a rogue-like game, 
where the Gods of Olympus assist Zagreus in his attempt to escape his father's realm, the Underworld. 

On each escape attempt, the assistance from the Gods are randomized in both what Gods offer their assistance, and what skills you are offered. 
Choosing the right skills are vital in order to improve your chances at succeeding in the run.

## Run the GUI

The Tkinter library for Python was used in order to create the GUI. 
PyInstaller was used to convert the python script into and exe for windows, such that the user does not need to install multiple 
libraries to run the script.

To run the GUI, download all files in the repository to an empty directory, and simply run the `duo_boons.exe` executable.

## Understanding the GUI

Zagreus has the following basic skills:

* A - Attack
* S - Special
* C - Cast
* D - Dash
* W - Wraith / Aid
* R - Revenge

When selecting certain skills from certain Gods, there is a chance to obtain an even stronger passive spell, known as a duo spell. 

In order to obtain a duo spell from two Gods, you must have a specific skill from both Gods in order to satisfy the requirement. 

In the GUI, simply select the God whose spell you have obtained, and in the text box underneath there will be a list of all 
requirements needed to obtain the duo spells. For example, in order to have a chance at acquiring the duo spell between Aphrodite and
Ares, the user must have either Aphrodite's attack, special, cast or dash, and must have either the attack or special from Ares 
(in other words, one basic skill listed in the GUI from both Gods). 

The GUI is intended to make it easier in deciding what route you will go when choosing God spells.

### Additional Information

In addition to the duo spell reqiurements, each God also has their own Legendary spell that you must fufill the requirements in order to 
have a chance at obtaining them. 

The following are needed to satisfy the Legendary requirement:
1. A specific basic skill from a given God
2. A specific passive skill from the same God (which also requires you to have fufilled requirement 1, i.e. you cannot get Are's 
Black Metal or Englufing Vortex without first getting either his cast, dash or aid.)

These requirements will be shown in the right text box, along with the specific duo skills (for quick reference). 
