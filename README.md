# Not functional and ugly, planning to rewrite

Those scripts are ones of the first I wrote, and actually they constitute my very first personal project. 
Thus the code is very messy, and I plan to rewrite it whenever I find some time.

# Personal assistant for GNU/Linux

GNU/Linux systems are missing personals assistants, therefore I decided to create my own by aggregating 2 technologies: 

* Google's speech recognition api
* Snowboy hotword detection

The program is integrated in my window manager status bar, as a widget. 


![off](http://i.imgur.com/joESFH2.png)

off mode



![on](http://i.imgur.com/W6EKsDN.png)

Assistant is listening for the triggering word. 



The code is messy and ugly as hell.
Some functionalites can be seen in the demo below.  

## Dependencies
* sox
* gtts
* Pyaudio
* numpy
* mplayer/mpv
* notify-send

## Demo
[Demo in french with artefacts and background noise](https://my.mixtape.moe/bwiadi.webm)


