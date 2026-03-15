# REPLACE THIS WITH YOUR GAME NAME

## Elevator Pitch

You are a security guard at a top secret facility. Each day you are given a program, and must use it to identify whether or not your co-workers are who they say they are, or if they are an impostor trying to sneak in. Each co-worker has a prefered variable and you must trace the given program to determine whether or not they have the correct value for the variable.

## Influences (Brief)

- *That's Not My Neighbor*:
  - Medium: Game
  - Explanation: This is the game the entire project is based on. It is a game where you are the doorman for an apartment building and must use a variety of clues to determine whether or not the people coming into the building are the people who actually live there, or if they are impostors trying to sneak their way in.
- *Papers Please*:
  - Medium: Game
  - Explanation: This game inspires the level progression of our game. Each day, there are more clues and the level gets harder, which is similar to how we want our game to run.


## Core Gameplay Mechanics (Brief)

- *Co-Workers*
  - You will interact with a variety of different co workers every day.
- *Your Clues/Programs*
  - Each day you are given *x* amount of programs/functions. 
- *Making Your Choice*
  - Based on the given evidence you must determine whether or not your co-worker is who they say they are.
- *Increasing Difficulty of Levels*
  - Each day your program will get more complex, as well as more co-workers and impostors trying to enter the building.
- *Victory vs Defeat*
  - You lose the game if you make too many mistakes, and win if you make it to the end of the week.

# Learning Aspects

## Learning Domains

- Functions and Function Calls
- Tracing Variables
- Pointers/Adresses

## Target Audiences

Introductory programmers and computer science students (CISC106/108)

## Target Contexts

This can be used in introductory computer science classes, as well as used as a study tool for anyone.

## Learning Objectives

*Remember, Learning Objectives are NOT simply topics. They are statements of observable behavior that a learner can do after the learning experience. You cannot observe someone "understanding" or "knowing" something.*

- *Variable Tracing*: Identify the value of a variable after a variety of function calls and value changes.
- *Pointers*: Correctly determine when a pointer changes the value of the original variable.

## Prerequisite Knowledge

- Explain what a pointer is and how one works.
- Ability to create a basic function with multiple variables.

## Assessment Measures

Can use a pre and post-test to determine improvement of the subject.

Given the following program, what is the value printed out by the print statement on line x?
- Can be multiple choice question
- Can be a short answer question
- Can have multiple different questions based on the same given program


# What sets this project apart?

- Many introductory computer science students struggle with identifying function calls and when the functions change the value of variables.
- Every programmer must be able to trace a program for coding and bug fixing purposes.
- This game gives students an environment where they can take their time answering the questions and fully understand how tracing the program works.

# Player Interaction Patterns and Modes

## Player Interaction Pattern

This is a one-player game where the player is provided with a program with a variety of variables. The player is then presented with supposed co-workers who will tell the player a value for a certain variable, and must trace through the given program to determine whether or not the value given by the co-worker is correct. The player will then click a button either letting the co-worker in, or kicking them out if they are an impostor.

## Player Modes

This game is a single-player game. You will progress through levels until you reach the end of the game.

# Gameplay Objectives

- *Let the co-workers in*:
    - Description: If the given variable value is correct, let the co-worker into the building.
    - Alignment: In order to determine if the value is correct the player must trace through the program and follow the given variable.
- *Kick the impostors out*:
    - Description: If the given variable value is incorrect, kick the impostor out of the building.
    - Alignment: In order to determine if the value is correct the player must trace through the program and follow the given variable.
- *Don't get fired*:
    - Description: Every day, if you let in too many impostors or get rid of too many co-workers, you will be fired. Your job is to avoid this.
    - Alignment: Gives the player a punishment for incorrectly tracing the program.
- *Get Promoted*:
    - Description: At the end of 7 days, if you have not been fired the CEO will congradulate you and give you a promotion.
    - Alignment: Rewards the player for correctly tracing the program.

# Procedures/Actions

The player will have two buttons to click. One will let the co-worker into the building, and the other will kick them out. The player will have a button where they can view and cycle through the given program and its related functions.

# Rules

- If the player lets in too many impostors they get fired and lose the game.
- If the player kicks out too many co-workers they get fired and lose the game.
- If the player makes it to the end of the week without getting fired, they win the game and get promoted.
- Every day the program will get more complex and the player will be faced with more supposed co-workers
- As the program evolves, it will encorporate the following:
  - Pointers
  - Function calls
  - References
  - Equations

# Objects/Entities

- Your office space (front desk)
- The different co-workers
- There is a clipboard that you click to view the programs
- There are two buttons on the desk thay you click to either let the co-worker in or kick them out
- Different cutscenes for the days/endings
- A queue of co-workers waiting to get in

## Core Gameplay Mechanics (Detailed)

- *Co-Workers*
  - The co-workers are the people that will be attempting to make their way into the building. Each co-worker will have a favorite variable and will tell you a value for that variable when they enter.
- *Your Clues/Programs*
  - Each day you are given *x* amount of programs/functions. It is your job to click through each and trace the variables to determine whether the co-worker's given value is the value that would be printed out by the print statement or if they are incorrect.
- *Making Your Choice*
  - Based on the given evidence you must determine whether your co-worker is who they say they are, and let them in, or that they are an impostor trying to sneak their way in, and reject them from entering. You have two buttons to make this choice, one for each option.
- *Increasing Difficulty of Levels*
  - Each day your program will get more complex, as well as more co-workers and impostors trying to enter the building. This increases the difficulty as the game goes on.
- *Victory vs Defeat*
  - If you let too many impostors into the building or get rid of too many co-workers, the impostors will steal all the company's code and you will be executed by the CEO. If you make very few mistakes in 7 days, the company will finish their top secret project and the CEO will be happy with you. If you make it through 7 days without a single mistake, you win the game and get promoted to become the new CEO.

    
## Feedback

- The player will be able to visually see the queue of co-workers waiting to get in so they know how many are left in the day.
- At the end of each day, the player will be able to see which co-workers they incorrectly assessed, as well as view the program for the day so they can go back and look at it now knowing the correct answer.
- When you lose the game, you get fired.
- When you win the game, you get promoted.

# Story and Gameplay

## Presentation of Rules

On day 1, the recently-promoted security guard will guide you through the job and how it all works while also assisting you with your choices. You will then be let loose on day 2 to play the rest of the game on your own.

## Presentation of Content

The game does not teach the player about functions and pointers. The player is expected to know that meterial before playing. The game's only purpose is to help the player trace a program.

## Story (Brief)

You are a new hire at a top-secret company. Your job is to make sure everyone entering the building is actually someone who works there, and not an impostor trying to sneak their way in. Every day you are given a program, and each co-worker is given a variable. Your job is to trace through the program to identify whether or not the value the co-worker states belongs to the variable is correct. Every day as the company gets closer to the deadline for the project, more co-workers will be coming in, and the program you are given will get more complex. At the end of the week, if you haven't been fired yet, you will be promoted by the CEO.

## Storyboarding

*Go into as much detail as needs be to visually convey the Dynamics of your game. Be detailed. Create storyboards and freeze frame images that concisely capture important key elements of your game. You are strongly recommended to sketch pictures on paper and embed them here. Be sure make it clear how previously-described mechanics come through in the dynamics.*

# Assets Needed

## Aethestics

The game has a darkish and gloomy aethestic, similar to *Papers Please*, but more office building-esque. The environment feels very secretive and protected.

## Graphical

- Characters List
  - Big Boss CEO: Will interact with you whenever you get fired/promoted
  - Intro Character (Steve): Will help guide you on day 1
  - The Variety of Co-workers/impostors
    - Kevin
    - James
    - Andrew
    - Joanna
    - Austin
    - Greg
    - Deborah
    - Ada
    - etc... (w.i.p)
- Textures:
  - Buttons
  - Clipboard
  - Monitor with queue
- Environment Art/Textures:
  - Wall in the background
  - Desk


## Audio


- Music List (Ambient sound)
  - Music: Darker and deeper, but not intense https://open.spotify.com/track/1QJflymJaad3iQ5DQhk8p1?si=966e4456dba749a7, https://open.spotify.com/track/3m8UfZwPMMbiWfGR8Lg2cR?si=72da290d5b25461b
  

- Sound List (SFX)
  - End of day: typewriter sound effect while text appears on screen
  - Loss Sound effect: Dark and death
  - Win sound effect: Victory and happy
  - New Person Arrives: Doorbell ding
  - Button press: button is pressed


# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3
