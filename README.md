# adventure.py

Greetings adventurer!
This program is a dungeon-escape text-based adventure. Through running `adventure.py`, you will be thrown in a cell and tasked to escape. 
At this time, the adventure has 12 total endings: 7 where the player character dies and 5 that can be considered 'good endings'.
More rooms and endings may be added at a later date. 

Typing input:

This game was designed to give the player freedom to type anything into the input field for each room. I think it adds a little spontanaeity 
not knowing exactly what all of your choices are and not being forced to type only 'yes', 'no', 'left', and 'right'. The player is free to type 
full sentences as long as key words are recognized. For example, if there is a character you want to talk to, you may type the character's name,
or `talk to {character}`, or `strike up a conversation`. I haven't put in all possibilities for user input, just what I thought would be most 
obvious or commonly used. If there is input the game doesn't recognize, a hint will be given for the options available in that room, and the user
will have as many chances as they like to type in a recognized input.

Typing `back`:

At almost any point in this program, you may type `back` to go to a previous room, although
sometimes a prompt will tell you that you cannot realistically go back and must continue forward. Typing `back` will not always lead
you to the exact screen you just left, as that wouldn't always make sense. Sometimes it will lead you to a room a few screens behind where
you are. You may not type `back` in the starting prison cell to get to the introduction page.

Exiting the game: 

At any point, you my type `exit` to quit out of the game. The game will always start back up on the introduction screen, welcoming you to the adventure.

Playing again:

After you have completed one ending, the game will ask if you want to play again. Typing anything other than 'Y', 'y', 'yes', 'yeah', 'yep', 
or any word containing a 'y' will exit the game. Typing a y-containing word will start you back in the first cell, skipping the intro screen.

Starting the game:

To begin the game, first `cd` into the directory in which you have `adventure.py`. Then all you need to do is type:

`python3 adventure.py`

and you're on your way!
