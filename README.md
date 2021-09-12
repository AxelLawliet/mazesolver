# mazesolver
This a maze solver/shortest path finder program using BFS algorithm.
-----------------------------------------------------------------WELCOME------------------------------------------------------------------
THIS IS THE README FILE TO THE TERM PROJECT MADE BY:
             ANKIT RAI 
	           MCA 2nd SEM
AS A TERM PROJECT OF DATA STRUCTURE FOR THE FOLLOWING SEMESTER

---------------------------------------------SOFTWARE & TECHNOLOGIES USED AND HOW TO USE THEM---------------------------------------------

THE FILE ATTACHED ALONG WITH THIS README FILE IS THE CODE OF THE PROJECT WHICH I MADE TITLED:
				      MAZE SOLVER USING BREADTH FIRST SEARCH (BFS)

WAYS TO VIEW THE OUTPUT:

1. RUN THE ATTACHED CODE, THIS WILL REQUIRE SOME ALTERATIONS. FURTHER DISCUSSED

2. RUN THE EXECUTABLE FILE, ATTACHED IN THE FOLDER. NAMED: maze.exe


THE CODE IS IN PYTHON, AND IT USES VARIOUS LIBRARIES LIKE TURTLE, PYGAMES etc. TO RUN THE CODE EFFICIENTLY. ONE MUST HAVE THESE INSTALLED
IN THEIR MACHINES. 


TO INSTALL THEM, YOU COULD REFER TO THE ARTICLES:

1. Python: Installing python is very easy, You can either download it from the Microsoft Store, or its website that is, 
				https://www.python.org/downloads/.

	Later on, you have to do certain setups, to ensure that the code works in the code editors.
	Here I am providing the setup for VS Code.
				https://code.visualstudio.com/docs/python/python-tutorial

2. Turtle: Turtle is a python library that enables users to create pictures and shapes by providing them with a virtual canvas.
	One can install Turtle, easily, by following some easy steps:
			https://turtle.readthedocs.io/en/latest/installation.html

	or, simply, write: 		$ pip install turtle

3. PyGame: This can be downloaded using this very link:
		https://cs.hofstra.edu/docs/pages/guides/InstallingPygame.html

-------------------------------------------------------------------NOTES-------------------------------------------------------------------

Note: The setups given above are a must, however you can run it on any online compilers, but if you want to do it on your system, the above 
procedures have to be followed strictly.

Note: As the code is being copied from the code editor to MS Word, there might be some indentation errors, when you run it on other 
	system after copying it from here, there might be chances for indentation errors. 

The Code editor I used for this is: VS Code

Note: You have to alter the main function for using other mazes, namely grid1, grid2, gird3, grid4, grid5. The information is provided
	below

--------------------------------------------------------------SOME REQUIRED ALTERATIONS----------------------------------------------------

The example is: 

Example 1:
# main program starts here ####z
setup_maze(grid1) 				//The maze used here is Maze #1 (Here change is to be made)
search(start_x,start_y)
backRoute(end_x, end_y)
wn.exitonclick()

Example 2:
# main program starts here ####z
setup_maze(grid2) 				//The maze used here is Maze #2
search(start_x,start_y)
backRoute(end_x, end_y)
wn.exitonclick()

Just like this one can make various grids of their own and setup different Mazes

For using other mazes please, alter like the above examples. The other mazes are namely :   grid1   -> For Maze 1
											    grid2   -> For Maze 2
											    grid3   -> For Maze 3
											    grid4   -> For Maze 4
											    grid5   -> For Maze 5

--------------------------------------------------------THANK YOU-------------------------------------------------------------------------
