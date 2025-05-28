[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/zon3mdIg)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19130199&assignment_repo_type=AssignmentRepo)
# Project Instructions
Follow the instructions here: https://vuxcode.netlify.app/new/pr1/lessons/major-project-brief/

REMEMBER TO "COMMIT" YOUR CHANGES REGULARLY TO SHOW HOW YOU HAVE BUILT THIS PROJECT! 

The final program is not the goal! The aim of the project is to show how you have developed your program, the steps you have taken and the problems you have solved!

# Project Notes

> 2025-04-24 
- The plan for this work time is to have a manin page (index.html) and connect the other pages (setting.html & game.html) via buttons from the index.html.
- From the game and settings page there is a button (Back to menue) that the user can click its way back to the main page. The problem here was to find out how to connect to another page, but luckily I made it. I also adde a about page. 
- old note and with some help of Google I manage to figure this out.

>2025-05-03 
Trying to create the game. I have manage to create the code for the boxes and name tags. I had som problem to figgure out how to link the correct color to the text. I also had som problem whit the math.floor function. The game does not work the way I want. All the buttons have the right color and name. Only one button shuld be uniq..

2025-05-08
Trying to fixa a slider and a savings button in the settings page. I got stuck when tying to solve how to save the data in the settings. The data need to be saved in to the game page. The function of the slider is to abb or increas the number of boxes in the game page. 

2025-05-08
Fixing the posision of the slide and save button. The slider and the button was placed in the upper left corner.

2025-08-08 No time i registrated
Removing the the test with the reault box after 10 clicks.

2025-08-14
I made some changes in the code. The code is more easy for me to follow. Instead of one variable, I now use two (randomColorIndex and randomLableIndex) to handel the colors.
The problem I had that all buttons had right color and labels in now solved. The solution = a while loop that contains both color and labels. 
I added a counte and a timer. The timer starts hen the player starts klicking. The counterstarts counting after each rounds in the game function. In the last I got a tip frpm Colin about localStorage. 
I manage to find out a solution for this. I als added JSON function. I don't know if this is OK for the project. There is NONO regaring OBJECT, but thius function only converts to a array. 

2025-05-14/15
Added container and increased sliders and buttons to the setting.html page. 
* Slider - Number of Boxes: Increas the number off boxes to the game.thml page. The default value is 3 boxes. Next step is to show the actual value to the righte of the slider.
* Slider - NUmber of Series: The same goes for this slider. The number to the left only uppdates 
* Slider - Numbers of Colors:
* Button - Dark Theme: Only button is added. 
* Button - Save: The button store the updated value. Started working on how to change the Number Of Series in game.html, but unfortunately I haven't managed to crack it yet. 
  The idea is to copy the procedure used when I send data to the scoreboard from the game.html page. 

2025-05-15 (after school)
* Created the function updateSliderValue that saves the value direct to the localStorage. Usin addEventListner and it updates the box value automatic for each slider. Now I don't need to update the page manualy.
* Trying to connect the Number of series in setting.html to the game.html. I thought I could simply replace the fixed value with Series from localStarage. Didn't work.

2025-05-21
game.html:
Under the global variabels, I get the value from localStorage(serials) and store the value in NumberOfSeries.  
I changed the IF stament (the IF statmen that handel the correct clicks) that the IF correctClicks === numberOfSeries, If not shuffel a new round.

setting.html
saved the value from Numbers Of Series to localStorage. 

2025-05-26/27.
Trying to solv the problem with the unique box. I have changed the program but still got the same rsault.
By using the array usedCombinations (includes the combination of color and label), I thougt the problem was solved. But not!! I have no more ideas how to solv this.  

2025-05-28.
Created at function in setting.html thah clear the scoreboard in index.html. I also added a new butten 'Clear Scoreboard' int eht setting.html page.

# Project Summary

This projekt has been enyoyable, yet challenging experience and has demanded a significant amount of time and effort. 
The time I have reported is not entirely accurate, as I workde on  small segments during lunch breakes at work and in the eavenings after my children went to bed. You can easily add an 5-7 houers to my reported time.

In addition to the functionalities and code examples demonstrated by Colin during our lessons, I have discovered other examples and techniques that could be useful to know. For instance, I explored ways to send data using JSON and localStorage, which I found particularly intriguing and practical.

Overall, this project has inspired me to dive deeper into programming and continue exploring its many possibilities.

# User Guide

> Write a clear user guide for how someone should use your program.