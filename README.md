===========
What is it?
===========

Acts as an extension for the Music On Console Player (MOCP), but can be altered to 
act as an extension for any music player.



=============
Documentation
=============

This program adds the following functionality to a music player, if it doesn't have
it already:
    
    - Playlist creation
    - Add songs to a playlist
    - Remove songs from a playlist
    - Print the songs in a playlist
    - Search for a song in the music library and play it.
    - Queue any song in the music library using the search function.

Further documentation can be found in the header of the program.



============
Installation
============

Install the Music On Console Player:
    
    # pacman -S moc

Update your PATH environment variable in your shell rc file with:
    
    $ export PATH="${PATH}":"/PATH/TO/PROGRAM/play"

Now the program is ready for use!



========
Contacts
========

If you have any problems, feel free to email me at 'gabeg@bu.edu'.



==================
Potential Problems
==================

- If you are receiving an incorrect file path error, check the ".pref" files in the 
  "log" directory and verify that the paths and playlists are correct.



=====
To-Do
=====

- Edit the "playlists.pref" file from the command line
