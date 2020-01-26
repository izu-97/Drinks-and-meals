# Drinks-and-meals


## Tequila Quillas:
#### Maximiliam Albrecht
#### Mateo Izurieta
#### Iván López

##### BER-01-20
##### 2020-01-27


## Project Description
Facing the daily question: what I could eat tonight? The deliverable is an executable file on jupyter notebook, able to guide the user for a search based on different criterias (type of food, ingredients,...) where finally recieves the complete recipe. The user-case also is extended to prepare cocktails and other kind of drinks.
A public API provides the information, so is not stored locally, but fetched from the provider. Therefore, Internet connection is mandatory. Transformations in the data frame provided are executed to adequated the visualisation to the user taking in consideration the features of the Jupyter Notebook


## Questions & Hypotheses
We set what we can call "interactive consulting database", solving the problem of decision making in regards eating or drinking, displaying several options according to user election


## Dataset
Information is provided by Open API Dataset

For drinks and cocktails: https://www.thecocktaildb.com/api.php

For meals: https://www.themealdb.com/api.php


## Database
The access to the information is structured in 3 or 4 steps (depending the path chosen by the user). 
First election is to set "Drinks" or "Meals" which defines the specific API to use (but both with equivalent structure).

The search allows to type the name of the meal (partial typing is allowed), which returns a list of matching options.

Selecting a specific option provides the final information of the recipe.

Additional step are necessary if the user chooses category or origin: a list of options are displayed. Depending the selection, it will narrow down the list with the different meals or drinks, till preferred election will display the complete recipe. 


## Workflow
After a brainstorming session, we had a list of ideas. Among them, we researched for different sources and made short attempt to have a prototype done (to check if it is "doable" in the limited period of time).

Once we decided for the "Meals and Drinks" option: we focused in the user-story, defining the different steps and building a flow diagram, which points the different functions that we need to develop.

We split the functions and created parallel, assembling the pieces in a fully functional script.

We run for 2 more iterations, adding components to improve the functionality and display, following the same pattern: splitting the functions, develop in parallel and assembling together.


## Organization
Initially we set a Trello board, but considering the short time available and the split of the tasks, we didnt use it in the final steps (maintenance of the board was an additional task that we considered unnecessary given the short term project. 

We arranged a informal but systematic approach: regular short meeting (3-4 times per day) to assemble the developed components, evaluate impact (QA & fine tune), briefly discuss additional possibilities, decide for specifics features to add, split them and work in parallel till the next meeting. 


## Folder contains:
### README.md

### Main.ipynb
File containing the functions to execute with Jupyter Notebook
https://github.com/izu-97/Drinks-and-meals/blob/master/Main.ipynb

### project3-drinks-and-meals.jpg 
structure diagram in image format
https://github.com/izu-97/Drinks-and-meals/blob/master/project3-drinks-and-meals.jpg

### Ignore
folder contains the different files we generated along the process, unnecessary for the evaluation of the project but relevant for the authors as "notes" and "backups files".