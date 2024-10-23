# Minesweeper-Game
Minesweeper game inspired by [Google's application](https://www.google.com/search?q=minesweeper&sca_esv=a54abf1cb7933d7b&rlz=1C1UEAD_enUS971US971&sxsrf=ADLYWIJ7t0ej46PbSP8J5wgsgSXg7N18eQ%3A1729613377200&ei=Qc4XZ63cC72i5NoPs_728Qk&ved=0ahUKEwjtgMn3r6KJAxU9EVkFHTO_PZ4Q4dUDCA8&uact=5&oq=minesweeper&gs_lp=Egxnd3Mtd2l6LXNlcnAiC21pbmVzd2VlcGVyMgoQIxiABBgnGIoFMhAQLhiABBixAxhDGIMBGIoFMhAQABiABBixAxhDGIMBGIoFMhAQABiABBixAxhDGIMBGIoFMg0QABiABBixAxhDGIoFMgoQABiABBhDGIoFMgsQABiABBixAxiDATIKEAAYgAQYQxiKBTIKEAAYgAQYQxiKBTIIEAAYgAQYsQMyHxAuGIAEGLEDGEMYgwEYigUYlwUY3AQY3gQY4ATYAQFIog5QAFirDXAAeAGQAQCYAWqgAdAHqgEDOS4yuAEDyAEA-AEBmAILoALQCMICBBAjGCfCAgoQLhiABBhDGIoFwgIFEAAYgATCAg0QLhiABBixAxhDGIoFwgIFEC4YgATCAggQLhiABBixA8ICEBAuGIAEGLEDGIMBGBQYhwLCAhAQABiABBixAxiDARgUGIcCwgIfEC4YgAQYsQMYgwEYFBiHAhiXBRjcBBjeBBjgBNgBAZgDALoGBggBEAEYFJIHAzYuNaAHino&sclient=gws-wiz-serp).

This game was made using Java in Eclipse IDE using Northeastern Univeristy's [Image Library](https://course.ccs.neu.edu/cs2510h/image-doc.html). Source code can only be accessed by request due to plagarism standards. 

## Game Rules
- On start screen, select difficulty (how many mines to play with) by using the up/down arrows
   (reccommended to play with 9 or 12 mines for medium level difficulty)
- Mouse click on the screen to start the game
- At the bottom of the screen, you will see your score, elapsed playing time, as well as how many flags 
   you are able to use (the amount of flags you are given is 2X the amount of mines on the board)
- To play, left-click any unrevealed cell (green color cells), and infer which cells to click using the 
   displayed number of surrounding mines and the revealed cells (sand color cells)
- You are awarded 10 points every time you successfully reveal a cell that does not contain a mine
- If you think an unrevealed cell has a mine, you may right-click the cell to flag it
- To remove a flag from a flagged cell, right-click the cell again
- If you attempt to reveal a cell that contains a mine, you lose the game
- If you successfully reveal all cells that don't have mines, you win!
- Have fun :))

https://github.com/user-attachments/assets/0ba692a1-b2ea-4db6-8b49-8bea56b2b1ae

## Instructions for Download (with requested source code)
1. Install and set up EclipseIDE application
2. Download *Minesweeper.java* file and *javalib.jar*, *tester.jar* files
3. In the File Menu, select *New* then *Java Project*. Select *Finish* and name the file whatever you would like
4. Highlight your new project in the Package Explorer pane, then right-click it and select *Properties*. Select the *Java Build Path*, then the *Libraries* tab, then click *Add External JARs*. Select the *javalib.jar* and *tester.jar* files to import
5. Then, in your project, highlight the *src* tab. In the File Menu select *Import*. Navigate to your directory that contains the *Minesweeper.java* file, select the file and click *Finish*

## Instructions to Play Game
1. Open the *Minesweeper.java* file in the *src* folder under your project
2. Click the *Run* tab, then *Run Configurations*
3. Name the configuration whatever you would like, select the *Project* as your project, the *Main Class* as tester.Main, then (under the *Arguments* tab) enter "ExamplesMinesweeperWorld" for *Program arguments*.
4. Finally click *Run* and play the game

