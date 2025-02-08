# Assignment2

There are four parts for assignment 2:
- [ ] Part 1 - Writing a program that uses multiple classes
- [ ] Part 2 - Fixing mistakes to understand common errors in Java syntax and interpret error messages accordingly
- [ ] Part 3 - Writing methods using core java constructs
- [ ] Part 4 - Starting your game development to put your learning into practice in a creative way

## Part 1: Modeling Wellesley's CS111 Class
In the first task of the assignment, you will employ object-oriented programming principles to model a section of CS 111. You will create student and professor classes to represent students and professors, and provide methods that will allow you to get statistics about the class.

Goals of this part:
 * Practice with OOP principles to create a simple object-oriented programming structure.
 * Practice quantitative reasoning and mathematical skills through creating QR-based instance methods.
 * Declare variables and create instances of classes.

It is recommended that you move through the assignment in the following order:
1) The Professor class
2) The Student class
3) The CS111 class

## Part 2: Recursion
Complete the questions about the two recursive methods in `Assignment2.pdf`.

Goals of this part:
 * Practice tracing and understanding recursive methods.

## Part 3: Text-Based Adventure Game
In this section, you will write your own methods and first Java program to model a well-known game. This requires effective command of Java constructs, 
including some APIs we introduced in class (Scanner and Random). You will continue to build your skills with loops, conditionals, and more Java constructs throughout the semester. Complete the file `RPS.java` for this task.

Note: There is some code in this starter file that we have not yet covered in class (arrays). You do not need to write any array-related code to complete this assignment. This is a chance to see an up-coming topic. 

Goals of this part:
 * Understand how to compile and run a simple Java program to interact with user input.
 * Gain experience with BlueJ, output, and interacting with Java programs.
 * Write effective Javadoc to ensure outside users can easily comprehend the purpose of code.
 * Create a Java class that manages specific state and behaviors.
 
## Part 4: Introduction to Adventure Games
Throughout the next assignments in this course, you will be developping different components for your own text-based adventure game. You must choose your own theme for your game and you will be able to add your own creativity to this part of the assignments. This game will be broken down for you into manageable parts, each tackling topics related to the course. This is meant to provide you with hands-on project experience, which you may include on your resume or GitHub profile in the future. For this Part 4 in Assignment 1, we'd like you to start brainstorming a theme by playing the text-based games we've provided and reflecting on what aspects you might include in your game. Additionally, you will get a first look at what adventure game source code might look like.

### Task 1: Creating a Map for Your Adventure Game
In this task, we'd like you to draw a map of your adventure game. According to whatever theme you've chosen, chart a map (on paper!) of your game's world. This map must include the following elements:
 * Exactly 4 rooms, with one room that is initially locked. The rooms must have doors and they must all be accessible, meaning that no room should be disconnected from the rest of the rooms. You decide how many doors each room has, and how they are connected. It is possible that rooms have doors that to not lead to another room. Each room must have a name.
 * At least one treasure chest per room (all rooms must have a treasure chest), with the key to the locked room inside one of them, as well as at least two treasures (some food, some other treasures) per chest. Label these items in each room on your map.
 * Your map must contain at least 3 animals (real or fictional) with differing values for the damage they can do. Add these animals to three different rooms (only one animal per room, not all rooms need to have an animal) by listing them in their corresponding room and specifying their damage.

The requirement for this sketch is that it meets all of these criteria and that it is legible and clear.
Feel free to be as artistic (or not) as you'd like.

### Task 2: First Adventure Game File
To begin programming your adventure game, open the files Game.java, Room.java, and Player.java from the starter code for this assignment. Start by looking at each class to understand how they are structured. Where is the `main()` method for your game? Where does the game ask for user input? What is the relationship between the three classes?

Your task is to complete the `TODO` items in each file to obtain a working game. Once your game is functional, it will be able to run as such:
```
You are starting in: Dungeon A dark, cold stone room
Welcome to the game! What would you like to do?
You can type 'go North', 'go South', 'go East', go West'
>>go North
No entry, player did not move.
You are now in: Dungeon A dark, cold stone room
>>>go East
You are now in: Cottage A warm cozy cabin
>>>go South
You are now in: Forest A dense evergreen forest
>>>go South
No entry, player did not move.
You are now in: Forest A dense evergreen forest
```

Here is a summary of the TODO items:
* In `Game` you will need to instantiate objects for the four `Room` objects of your game and add neighbors for each one to resemble the map that you created for your game. You will need to use the `getNeighbors()` method from `Room` which is already defined for you.
* In `Game` you will also need to create an introductory text similar to `Welcome to the game! What would you like to do?` but using your own creativity.
* In `Room` you will need to override the `toString()` to print a `Room`
* In `Player` will need to create multiple getter and setter methods, and override the `toString()` method

## COLLABORATION
This assignment is an individual assignment. You can discuss this assignment with your peers, TA and instructor. You cannot show code to your peers, you each write your own solutions. You can show code to the TAs and instructor. Additionally, you cannot use generative AI or online resources that are not linked from our course website to complete this assignment.  

## SUBMISSION
Submit the following files to Gradescope for Assignment 1:
* take a picture of your solutions to Part 1 and upload a .png or .jpeg file to Gradescope
* take a picture of your game map and upload a .png or .jpeg file to Gradescope
* upload your solutions to `Mistakes.java`, `RPS.java`, `Game.java`, `Player.java`, `Room.java` to Gradescope

Note: You can resubmit your assignment as many times as needed until the deadline. Every time you resubmit, make sure you submit *all* of the files for your assignment every time.

## GRADING RUBRIC
Your assignment will be graded on accuracy, code style (including good name conventions for methods and variables you create, indentation, clean code) and meaningful documentation. Make sure that all of your files have header-level javadoc descriptions and that all of your methods also have javadoc. Include in-line comments sparsely, only to explain code (or a programming decision) that is not self-apparent.

## ASSIGNMENT SOLUTIONS
Assignment solutions will not be shared. If you did not get full credit on the assignment, you should review the feedback and ask me or the TAs if you have further questions. 
