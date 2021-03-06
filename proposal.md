# X-Team 27 Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description
We need to be able to make music playlists of songs that we like.<br>
We could have a pointer in an array for genre/playlist and in each pointer we could have some sort of BST that would have songs inserted into it with each song having data for name, artist, genre, etc.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)<br>
Music Playlist



2. Output: Describe the output your program will produce.  Include and example format of the output produced.
The output should display the song title, artist, and play time. <br>
The playlist should also be displayed with the song genre as well as the runtime of the playlist and upcoming songs along with its artist, and runtime. <br> <br>
Current song:<br>
Song Title: song name <br>
Artist: artist name <br>
runtime <br> <br>
Name of Genre <br>
runtime of playlist <br>
Upcoming song #1 info: Title - artist - time <br>
Upcoming song #2 info: Title - artist - time <br>
Upcoming song #3 info: Title - artist - time <br>


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
song input
<br> song name
<br> genre
<br> artist
<br> length
<br> album
playlist input
<br> genre
<br> number of songs or run length
<br> artists

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

 We will be using a text based interface e.g. menu for our Music Playlist program.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.Name each interface or class and briefly describe its function or purpose.


### PlayListBST:
 Contains several song nodes inserted into a BST
 
### SongNode:
Contains data on information such as song name, artist, genre, etc.

### Main: 
Contains an array where each part of the array can point to a PlayListBST.

### Some Testing Ideas: 
-When retreiving a song we want to test if we are looking for null, also if the song isn't in the playlist we should receive an error.<br>
-Throw error if song length is negative or if inputted in unexpected format rather than 01:23<br>
-If the number of playlists exceed the max allowed(or if we want to have it expand)<br>
-Usual problem values such as null, 1, 0, "", " "<br>
-Also test large numbers of songs being input


## Edit and Submit this file and any figures referenced by this document.

