![Alt text](https://github.com/matthewsides/Project02-HigherorLowerGame/blob/master/higherorlowerlogop2.png?raw=true "Optional Title")

| Version 1.01    |
|-----------------|
| 28 November 2017|


# Revision List

| Version     | Author          | Date                 | Comments                       |
|-------------|-----------------|----------------------|--------------------------------|
| 1.00        |  Matthew Sides  |              2017    | Initial Version                |
| 1.01        |  Matthew Sides  |              2017    |                                | 
|             |                 |                      |                                | 
|             |                 |                      |                                |
|             |                 |                      |                                |
|                                                                                       |                         


# Table Of Contents

[1] Introduction 

[2] Scope

[3] Type Conventions
     
[4]  Research

[5] References 

[6] Target System 

[7] Specification 

[8]  High Level Non-Functional Requirements

[9] High Level Functional Requirements

[10] User Stories

[11] Project Backlog

[12] Flow Chart

[13] Process of implementation Algorithm

[14] Description of IDE used and features it provided

[15] Logic Behind the IDE used in project 2

[16] Debugging process and debugging facilities in your chosen IDE

[17] Coding Standard 

### [1] Introduction

This document specifies a design for the conceptual features and mechanics (gameplay) of a game with the provisional title “Higher or Lower” . It is based on elements found within a given brief specifying for a game based around the popular card guessing game Higher or Lower. 

### [2] Scope

This documentation is intended to be read by programmers, artists and producers involved in the design implementation and testing of the HTML internet game "Higher or Lower".

### [3] Type Conventions

Things that have been discussed in a meeting are presented in this document with no asterisks.

Things that have not been offically agreed on but which are suggested by the author are presented with asterisks, like this (*),being marked as omitted until it has been agreed upon that it may be of use or implemented.


### [4] Research

This segment marks 

### [5] References

N/A

### [6] Target System
The Higher or Lower application will be produced for the following platforms: Windows all versions running on the command line, written in C++ using the IDE repl.it (online IDE). This Documentation is primary concerned with the command line and functionality aspect though maybe expanded and rebooted to make the game more graphically adept and functional in browsers or as its own seperate program.

### [7] Specification 

A Higher or lower card game based around playing cards being the aesthetic, allowing a user to be given a card or value then guessing whether the next value will be higher or lower in conjunction or comparision to the initial value. If the user is correct in their assumption they are to be visual awarded somehow or notified whether they were right or wrong.

### [8] High Level Function Requirements


### [9] High Level Non-Functional Requirements



### [10] User Stories

As a user i would like to be able to see a number on the screen. -  see number representation.

As a user i would like to be able to get allocated a virtual amount of currency. - get allocated a virtual amount.

As a user i would like to be able to get given a card. - get given card.

As a user i would like to be able to input whether the next card is higher or lower than the card I already have. - input higher or lower.   

As a user i would like to be able to get feedback as to whether I was right or wrong. - get feedback.

As a user i would like to be able to see the allocated virtual currency number change either going up or down.- see allocated number change.


### [11] Project Back Log

| User Story  | Description                  | Points | Due Date | Mo | Tu | We | Th | Fr |
|-------------|------------------------------|--------|----------|----|----|----|----|----|
| 1           | See number representation    | 2      | July     |    |    |    |    |    |
| 2           | get allocated virtual amount | 3      | July     |    |    |    |    |    |
| 3           | get given card  (value)      | 5      | July     |    |    |    |    |    |
| 4           | input higher or lower        | 4      | July     |    |    |    |    |    |
| 5           | get feedback                 | 2      | July     |    |    |    |    |    |
| 6           | see allocated number change  | 3      | July     |    |    |    |    |    |
| Total Points| 19                           |



### [12] Algorithm - (Flowchart)

<img src="Project02/FlowChartP2.jpg" alt="Project2"
     title="Project2" />
     

### [13] Process of implementation Algorithm

The program was initially broken down into segments, the first proccess consistng of getting a random number, using said random number as a representation of the first or initial card intended to be given to the user. The random number function or generator once implemented was intended to be used for multiple uses thus two variables were created to store both the initial and final number.
Though before the second number was printed a user input question linked to cin (console input) was applied, furthermore multiple conditional statements checking as to whether the input is corresponding to the pre-set inputs (higher or lower), else re-loop, which extends onto the next implementation or proccess a loop using while, for and do loops to continue to loop the game until predetermined or acceptable input is retrieved.The second variable then came into play setting the basics into fruition as once input is given another random number seperate to the previous one is displayed.If one of the conditions is met either the program re-loops for more input or states that the user has either won or lost. Thereafter the game loops no matter the outcome the next line of printed words were set to be printed 15 lines down to stop the console from getting cluttered and create the illusion of the game updating (refreshing). Once the higher or lower game structure was formed an end setting or end condition (event) was incorparted in the form of virtual money and two bars in which to aspire to get too or not, one leading to the user winning the game, the other seeing the user lose. The win condition in this instance consists of getting a numerical value of 1000 in the money, whilst the lose condition was geting under 0 (Value).

For the conditions a variable was defined holding a pre-set value, in which the variable was printed continously during every refresh to show the change in numerical value. Moreover within the if statements and conditinal statements underneath depending on the situation or instance a 100 numerical value was subtracted or added.


### [14] Description of IDE used and features it provided

The IDE ( Integrated Development Environment) used was repl.it, the features it provided consisted of a debugger (find problems), compiler (run the code), explorer (find files), source editor (text editor),form builder, data dictionary, data file viewer.

![Alt text](https://github.com/matthewsides/Project02-HigherorLowerGame/blob/master/idereplit.png?raw=true "Optional Title")

### [15] Logic Behind the IDE used in project 2

The Intergrated Development Enviroment or IDE for short (acronym) used in the development as briefly covered above was repl.it, the reasoning behind this is due to the ability to link the code directly to a Github repository or storage and consistently save the code and the coding language required (C++) being compatible with the IDE. Whilst the inclusion of two seperate windows that enable real time usage being able to test and view the outcome without having to use another program or go into another window was a turning point in the decision as to which IDE should be used to develop project 2 (Higher or Lower Application). 

### [16] Debugging process and debugging facilities in your chosen IDE

The Debugging proccess consisted of using the facilities given by the IDE which was to print errors as to what was wrong and pointing me into the direction as to what line or lines were incorrectly coded or were causing problems. Thus once re-directed to the line after reading the feedback given a response was given as to whether I should alter the code directly or if more research is needed.

### [17] Coding Standard

coding standards are version-independent and "always-current". All new code should follow the current standards, regardless of (core) version. Existing code in older versions may be updated, but doesn't necessarily have to be.  The coding standards applied for this particular project are similiar to those used by Drupal (Drupals coding standards).

#### Indenting and Whitespace

The indentation in the project uses indentation when nesaccary to show what is a sub-set or sub-servant of what, this is particularly shown within the conditional statements and under the loops.

![Alt text](https://github.com/matthewsides/Project02-HigherorLowerGame/blob/master/codeindentation.png?raw=true "Optional Title")

Moreover the new line function (\n) was used to avoid the verbose "\ No newline at end of file" patch warning, whilst also making the file easier to read as using the clear command for the command console was not practical or robust.

#### Operators

All binary operators (operators that come between two values), such as +, -, =, !=, ==, >, etc.(should) have a space before and after the operator, for readability. 

#### Casting 

Put a space between the (type) and the variable in a cast: (int) variablename.

![Alt text](https://github.com/matthewsides/Project02-HigherorLowerGame/blob/master/casting.png?raw=true "Optional Title")

#### Control Structures

Control structures essentially relating to if, for, while, switch, etc. Here is a sample if statement with else u sed in the project and a do/while encasing the if statement (though not visible in the below screen shot since it evelopes the whole code not just the below snippet):

![Alt text](https://github.com/matthewsides/Project02-HigherorLowerGame/blob/master/controlstatementif.png?raw=true "Optional Title")

#### Line Length and wrapping

The ideology was used whilst developing the project that conditions (conditional statements) should not be wrapped into multiple lines.

Whilst Lines containing longer function names, function/class definitions, variable declarations, etc were not allowed to exceed 80 characters. Though conditiona; statements may as long as its purpose is conveyed or portrayed clearly.Furthermore comments are allowed to exceed the limit, though must be moderated still to ensuring the code is not impossible to locate as it is overwritten and encased in comments. 

#### Function Calls

The functions in the project were called with no spaces between the function name, the opening parenthesis, and the first parameter; spaces between commas and each parameter, and no space between the last parameter, the closing parenthesis, and the semicolon. Here's an example in the project code:

![Alt text](https://github.com/matthewsides/Project02-HigherorLowerGame/blob/master/codefunctioncalls.png?raw=true "Optional Title")



#### Quotes

There wasnt really a standard for the use of single quotes and double quotes though in the project (within each module) there was an attempt to keep a certain amount of consistency.

#### Comments

There isnt a particular standard to commenting other than ensuring that the comments are clear and concise, the amount of characters a comment may exceed is not set though it is recommended and was attempted to keep the comments to either one or two lines.

![Alt text](https://github.com/matthewsides/Project02-HigherorLowerGame/blob/master/codecomments.png?raw=true "Optional Title")

#### Naming Conventions

Functions should be named using lowercase, and words should be separated with an underscore. Functions should in addition have the grouping/module name as a prefix, to avoid name collisions between modules.

Variables should be named using lowercase, and words should be separated either with uppercase characters.

![Alt text](https://github.com/matthewsides/Project02-HigherorLowerGame/blob/master/codenameconventions.png?raw=true "Optional Title")





