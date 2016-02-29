# Demonstration

<a href="http://www.youtube.com/watch?feature=player_embedded&v=HJyRnrbuTlQ
" target="_blank"><img src="http://img.youtube.com/vi/HJyRnrbuTlQ/0.jpg" 
alt="Hanksmash In Action" width="240" height="180" border="10" /></a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/HJyRnrbuTlQ" frameborder="0" allowfullscreen></iframe>

# About

HankSmash is free software released under the Gnu Public License 3. The 
entire text of that license is available in COPYING.phm. 

Important: Credit is due to the following four individuals who
developed bambam:

* Don Brown
* Spike Burch
* Marcin Owsiany
* Bram Meleman

# Running

HankSmash requires PyGame to run. If you do not presently have PyGame 
and you are on a Debian-based system, run:

sudo apt-get install python python-pygame

Now:

1. Unpack HankSmash 
2. Make hanksmash.py and hanksmash.6 executable: 
	chmod +x hanksmash.py hanksmash.6
3. Launch the game:
	python hanksmash.py
	or
	python hanksmash.py --uppercase
			[for uppercase letters to be displayed instead of lowercase 
			letters]

Important: to quit, type out the word
**quit**
                                                
4. Optionally, you can choose to mute some or all of the sound effects 
in HankSmash.

	To mute only a specified noise, do
		python hanksmash.py --sound_blacklist data/sounds/<filename>.wav
			
			NOTE: FILES.phm lists all sound and image files included in 
			the data folder, complete with path.
			
	To mute all noise before the game even starts, do
		python hanksmash.py --sound_blacklist
        
	If you mute all noises before you begin, you will have to restart 
	the program in order to use ANY noises.
	So, in many cases you may just want to type out

**mute**

	to make it go silent and then 

**unmute**

	to bring the sound back.

5. When your child or you are done with the program, type out the word

**quit**
																		
# Notes

[Doodle Gum by imagex](http://www.dafont.com/doodle-gum.font) is used in this game.

