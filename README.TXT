Project: music-organizer-v4. A project to collect audio files.
Authors: David J. Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 4.

To start:

Create a MusicOrganizer object. This will scan the default audio 
folder for any mp3 files. The default folder is the one named
"audio", in the same directory as the project folder.

You can place your own mp3 files into this folder to include and 
play them. Just make sure the filename is of the expected format: 

  artist name-track name.mp3

part 4 
Q29: Added playCount field to Track, with methods to reset, increment, and retrieve the count.
Q30: Updated MusicOrganizer to increment playCount whenever a track is played.
Q31: Added a 'genre' field to Track class. Provided an accessor (getGenre) and mutator (setGenre) method to read and update the genre.
Q32: Modified MusicOrganizer so only one track plays at a time; previous track stops automatically.
Q33: Created a method findKeyExample() in the project. Declared a boolean variable found to track wether the key was fond. Used while loop to search through an array of keys ("A", "B", "C") until the key "B" is found or the array ends. Then printed out the posistion where the key "B" is found.
