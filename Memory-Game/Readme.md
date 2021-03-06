# DNA-Arcade
Modified version of the classic memory game

<br/>


![Game Menu](Screenshots/game_menu.png?raw=true "Menu")

![Select Difficulty](Screenshots/levels.png?raw=true "Levels")

![Game Board](Screenshots/Game.png?raw=true "Game Board")


### How to use
* To clone the repository:

 ```bash
 git clone https://github.com/Aksh77/Pygame.git
 ```
* Browse to Game directory :

 ```bash
 cd Pygame/Memory-Game
 ```

* Install the dependencies
 
 ```bash
 sudo pip install -r requirements.txt
 ```
 
* Compile and run the program :

 ```bash
 python DNA_Arcade.py
 ```
 
 
### Dependencies
* Python 2.x
* Pygame 1.9


### How to Play

This is the modified version of the classic Memory Game.
Instead of matching the tiles having the same object, you need to match the tiles having Complimentary Base pairs of DNA.

* **A** (Adenine) pairs with **T** (Thymine)  and **C** (Cytosine) pairs with **G** (Guanine).
* Both the tiles should have the letters with the same colour in order to match.
* The Game is won when all the pairs are matched.

### Features
3 Difficulty levels :

* Easy   (Board size: 4 X 4)

* Medium (Board size: 6 X 5)

* Hard   (Board Size: 8 X 7)

### To-Do

* Count Number of moves
* Save Highscore
* Add Sound effects
