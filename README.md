# Music-player-in-Python
Creating a music player in python by 
Importing all the libraries
Initializing the root window and pygame.mixer
Defining the play, stop, pause, resume and load functions
Creating the LabelFrames and StringVar variables
Placing all the objects in all the three LabelFrames
Creating the final Label that will display the status of the song
To make python music player project, we will use some elements in the music file of the mixer module. Those elements are:

.load(filename) – This method is used to load a file so that other actions can be performed on that file. The argument it takes is a file of a supported audio format [.wav, .mp3, .ogg].
.play() – This method is used to play the music file that was loaded by the .load() method.
.stop() – This method can stop the loaded file such that it cannot be resumed again.
.pause() – This method is used to pause a loaded file, at least with this option, it can be played again before needing to be loaded again.
.unpause() – This method is used to unpause a loaded audio file, also known as the resume option.
