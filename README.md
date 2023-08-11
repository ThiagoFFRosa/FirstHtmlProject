# FirstHtmlProject
That's my first project trying do develop a Web site for some professional objectives

thats not my first time using HMTL I have done some previous things using it but this time I have done some PLUS things soo, there is my experience.


First I have started choosing the page that I wanted to create soo, I first developed the page that gonna recieve the inputs to make my script work with.

so I created a FORM inside a "box-notas" and put some labels with no inputs.

the inputs I used a Java Script to recieve data from a CSV that I would recieve form who wanted the script from me.
   in the java script I needed some filtes in the inputs so it dosent make a mess in the user screen soo, I made a Filter in the reciever "TEAM" that when u choose a TEAM
   it does filter the categories that the TEAM where at and obviosly it clears the dupped ones as the TEAM opitions do, the same way the Names options receives only the TEAM
   and the categiries and filters the names, this one don't clear the dupped ones bks is the last one.

so after recieving the inputs it redirects the user to another hmtl page that recieves TEAM CATEGORIES and NAMES and with that info it works recieving the line that all that
info is stored in the CSV folder and adds in the collums of "points" the points that in the new HTML page gonna be input.
After recieving the inputs linked to the HTML page I have a php script to save everything in the csv file, the php script does a search in the TEAM CAT and NAME
finds the line that have all that info the same in the same line and in the following collums it saves all the inputs and it does a math and calculates the TOTAL.
btw the calc that I need to use is a bit different bcs it is from a specific competition soo it's not just making 1+1.

after all this I have created a NEW separated Page that recive the Score the names the team and the categorie and displays every thing.

# WHY?
in my script they wanted a live display with the notes to be displayed for the public so the public could follow the points from the competitors

some problems that I had and some advices

when displaying a info that recieves constant changes some times the script stop recieving the CSV file bcs it thinks its the same file so thats not a need to updade.
but some times the change is a bit different from the previous one and U need to display it 

so I used a command in html/Java that sees the timestamp from the file so it always gets updated.

the command.

->fetch('dados/AAAA.csv?timestamp=' + new Date().getTime())
# Some (different) features

- THEME SELECTOR

I wanted a option to change the theme from the page but, I didn't wanted to use a Java Script to make it soo then I made a copy from the pages and the java scripts(bcs the java script is used to link a button to the next page)

and changed the links of all the buttons to the same pages but in white theme.

- "burguer" Menu

I wanted a burguer menu to choose the tabs to see the painel to see the ranking and another to go to a more info page so I tried to use a normal burguer button but it didnt work pretty well then I give up and made a button that opens a side bar with the optins that I needed and in the button I put the image from a burguer button (real genius here)

- Json Problems

I have used a Json file to display the updated infos but I don't know WHY THE HEK it stopped working so I give up trying to understand why it stoped and I create another CSV file that would recieve the same info. anyways it works great!

last update 11/08/2023
