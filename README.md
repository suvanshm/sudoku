# Sudoku
Sudoku platform made using Pygame. Boards of various difficulties imported from www.websudoku.com through web scraping using Beautiful Soup. A recursive algorithm using backtracking to solve the board is also implemented as a solver feature. 

The game allows the user to play thousands of sudoku boards across three different difficulty levels and also have an option to solve any particular board. 

## Prerequisites and Deployment
* Python 3 - https://www.python.org/downloads/
* Pygame - https://www.pygame.org/download.shtml 
* BeautifulSoup4 - https://pypi.org/project/bs4/

The program is straightforward to deploy and has no special virtual environment requirements.

## Program Functionality
The UI Platform is displayed as follows. The board is set up to display an 'Easy' difficulty game by default. 

![](https://github.com/suvanshm/sudoku/blob/master/Photos/Capture.JPG)

The user can click 'Solve' to immediately solve any board

![](https://github.com/suvanshm/sudoku/blob/master/Photos/solved.JPG)

The square that the user selects for entry is highlighted. The user can enter key input. There is error handling in place to ensure only digits 1-9 are inputted.
![](https://github.com/suvanshm/sudoku/blob/master/Photos/Select.JPG)

The 'Check' button allows users to check if their board is incorrect, and it automatically highlights any squares violating the Sudoku rules. 

![](https://github.com/suvanshm/sudoku/blob/master/Photos/Check.JPG)






