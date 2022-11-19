# Tetris game Project

## Summary:
This is game showing my strength in the understanding of Python syntax and the use of the Pygame module that Python offers for game development.

### Requirements:
A Python IDE and Pygame module installed on the system( can be done with `pip install pygame`)

- To get the starter pack that comes with the shapes in the game, the game board and default colours download 
`https://pastebin.com/embed_js/VztMLjCc`, a starter pack file made by [`Tech with Tim`](https://www.youtube.com/@TechWithTim) - You can check his channel as it has really helped me in this project.

#### Expalnation of all the functions in icis_tetris.py:
##### Following the lines Chronologically we can see:
- Firstly, the import statements that imported `pygame` and `random` 
- We have the declaration of the Global variables, the shape format and colours.
- A class called `Piece` is made to initialize the shapes in the Tetris game.
- Functions:
 - `def create_grid`: used to make the board of the game.
 - `def convert_shape_format`: used to implement the logic used when the orientation of the shape wants to be changed by a player in the course of the game i.e as the shapes are falling down.
 - `def valid_space`: takes into the consideration the shape and the grid then uses that to check the parts of the Tetris game board that is still eligible for dropping bricks.
 - `def check_lost`: handles the logic of checking if we lost the game or not.
 - `def get_shape`: selects shape of blocks to be played at random.
 - `def draw_text_middle`: used to write a text at the middle of the board, can be implemented in any way. In my case I implemented it when displaying the default text to be displayed when a player loses.
 - `def draw_grid`: used to draw the gridlindes on the board.
 - `def clear_rows`: implements the feature of the game where the bottom row is cleared when it is completely stacked horizontally - [check the rules and logic of Tetris here](https://en.wikipedia.org/wiki/Tetris)
 - `def draw_next_shape`: creates a section for us to see the next shape to be placed in the board.
 - `def update_score`: updates the score and saves it to a file called scores.txt
 > Put a default digit in the scores.txt e.g `0`, before running as it helps this function work better.
 - `def max_score`: stores the max_score in the game session one has had.
 - `def draw_window`: initializes the game board.
 - `def main`: used to implement the whole game logic and usesa loop to keep the game in play.
 - `def main_menu`: shows the screen and prompts one to press a button before starting the game. This function calls the `main` function.
> That is all on functions, the other lines of code are quite easy to understand.

## Sneak pic of the game beforr you check it out :zany_face: :
![Game image](/game_pic.png)

