## Java Course Projects
A collection of my projects for the [Java track](https://hyperskill.org/tracks/1) at [JetBrains Academy](https://www.jetbrains.com/academy). These are the main tasks from the course without the exercises and with simplified folder structures. This makes it possible to run them from the command line without the need for the JetBrains IDEA ide.


### How to run
These apps were developed with Java 11. I did not test them on other Java versions.
That means you need the Java 11 JDK on your path.
1. Go into a project directory.
2. Run `./gradlew run` on Linux or `.\gradlew run` on Windows.

I advise against importing this repository from GitHub as one ide project. This may confuse 
the ide and result in very long loading times. Instead, you should clone the whole repository 
and open only the subdirectories as projects.


### Projects
This list is sorted chronologically. The projects at the top are my first ever Java apps and 
are therefore very simple and probably written in a bad and inefficient style. Please take 
that into account when checking out the code.

1. **[Coffee Machine](Coffee_Machine)**  
    My first Java project. A simple console app that simulates a coffee machine.
2. **[Tic-Tac-Toe with AI](Tic-Tac-Toe_with_AI)**  
    A tic-tac-toe app for the console. It lets you play either against another human or the 
    computer. It is also possible to watch the computer play against itself. The computer 
    has three difficulty levels. The easiest makes random moves, medium looks one move 
    ahead, and the hardest uses the minimax algorithm.
3. **[Sorting Tool](Sorting_Tool)**  
    This application sorts your inputs either naturally or by count. It can read the values from 
    the command line or a file and output the result either to the command line or a file.
4. **[Smart Calculator](Smart_Calculator)**  
    A calculator for the console. It supports addition, subtraction, multiplication, integer division, 
    and exponentiation. You can assign variables and group operations using parentheses.
5. **[Text Editor](Text_Editor)**  
    This is a basic text editor with a Swing GUI. It lets you load and save your text to files. 
    It also has a text search function with an optional regex mode.
6. **[Game of Life](Game_of_Life)**  
    Conway's Game of Life cellular automaton. With a Swing GUI that enables the user to start 
    and stop the simulation and step through it. The simulation and the GUI run in separate 
    threads.
7. **[Guess the Animal](Guess_the_Animal)**  
    This is a guessing game where the computer tries to guess which animal you are thinking of 
    via a series of yes/no questions. If it fails to give a correct answer it learns a new 
    animal and a fact to differentiate it from others. The data is stored in a binary tree. 
    Between runs this tree is serialized to either json, xml or yaml. In this project I also 
    practiced internationalization by providing an english and an esperanto locale.
8. **[Simple Banking System](Simple_Banking_System)**  
    A console app that lets you open bank accounts and deposit or transfer money. 
    Card numbers are generated and validated with the Luhn algorithm. The data are stored locally
    in an SQLite database. This very simple program was my introduction to SQL.
9. **[Web Quiz Engine](Web_Quiz_Engine)**  
    A REST API that provides access to a database of quizzes. Built with Spring Boot.
    You can register and authenticate users, submit quizzes, solve, and delete them.
    It is possible to get paginated lists of all stored quizzes and quiz completions per user.
    The data is stored in a local database.
10. **[Code Sharing Platform](Code_Sharing_Platform)**  
    In this project I am using Spring Boot to learn how to combine the backend and frontend by
    building a platform where users can share code snippets. You can access it in the browser
    to create new code snippets, see the latest codes, and access specific codes by ID. Code
    snippets are optionally access restricted by number of views or with a time limit. The data
    is stored in a local database file.
11. **[Car Sharing](Car_Sharing)**  
    A simple command line app that simulates a car sharing service. I used this
    project to repeat how to do SQL queries with JDBC.
12. **[Recipes](Recipes)**  
    A Spring Boot app that provides a REST API to manage recipes in a database. You can register 
    users, save recipes, get recipes, and modify them.
