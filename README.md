# Teletype scenes
## Spine
[![Spine on youtube](http://img.youtube.com/vi/8Ut7RuTwOpU/0.jpg)](http://www.youtube.com/watch?v=8Ut7RuTwOpU)  
Four parts, selected by knob, each part has it's own pattern (0-3)  

Pattern structure:  
rows 0-15: scale  
rows 16-23: melody  
rows 24-31: unused  
rows 32-47: probability of BD  
rows 48-63: a group of four consecutive notes form a chord, the first note in the group is the bass note

## Binary
[![Binary on youtube](http://img.youtube.com/vi/xWid0iosVOk/0.jpg)](http://www.youtube.com/watch?v=xWid0iosVOk)  

## Hi Five
[![Hi Five on youtube](http://img.youtube.com/vi/QhY-s0VNT2E/0.jpg)](http://www.youtube.com/watch?v=QhY-s0VNT2E)  
Tracks split over two scenes, selected on knob. For this to work the scenes must be in locations 7 and 8 (or edit the code, change "7" in the last two lines of script 8 in both scenes to the location of the first scene, the second scene must then be next from the first).  
First scene is the main part, scene 2 is a randomly generated break.


# Mom-series
My Mom has trouble sleeping at night, so I'm putting together a series of ambient pieces for her to relax to.
## Mom #1
[![Mom 1 on instagram](https://github.com/attejensen/teletype/blob/master/pix/mom_1.jpg?raw=true)](https://www.instagram.com/p/BwFW5GxBanv)  
Four parts, selected by knob, each part has it's own pattern (0-3)  
Each patterns contain notes, pattern 0 more basic (mostly octaves and 5ths), ranging to pattern 3, which contains more complex notes.  

Metro script randomizes itself  
Script 1-3 triggers one voice each on the ER-301  
Script 8 stops 

## Mom #2
[![Mom 2 on instagram](https://github.com/attejensen/teletype/blob/master/pix/mom_2.jpg?raw=true)](https://www.instagram.com/p/BwIAOgsB2Om)  
Three chords (C, F, Dm) selected on knob  
F6/F7 -/+ activity (0-100)  
F8 Randomize pattern start and length  

Pattern layout: 
Pattern 0: C-major chord  
Pattern 1: F-major chord  
Pattern 2: D-minor chord   
rows 0-15: notes for soft bleep sound  
rows 16-19: notes for strings  

## Mom #3
[![Mom 3 on instagram](https://github.com/attejensen/teletype/blob/master/pix/mom_3.jpg?raw=true)](https://www.instagram.com/p/BwzgmI2Feaz)  
Randomly select notes in a chord-like structure, knob determines probability that a note will play.

## Mom #4
[![Mom 4 on instagram](https://github.com/attejensen/teletype/blob/master/pix/mom_4.jpg?raw=true)](https://www.instagram.com/p/BxZZv1IBwQv)  
Three voices each going through a series of notes in C-major, knob controls the number of voices playing

## Mom #5
[![Mom 5 on instagram](https://github.com/attejensen/teletype/blob/master/pix/mom_5.jpg?raw=true)](https://www.instagram.com/p/BxaqHgfB1AB)  
10 partials from the overtone series on the er-301. Teletype radomizes gains and slews of those gain changes
