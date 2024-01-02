# Fantasy Travel Database
## Description
The purpose of this database is to provide information about the fantastic worlds, realms, and cities in other paradigms.
- I wanted to create this database which combines two of my passions: Travel and Fantasy.
- I built this database in order to showcase what I have learned so far through my level 5 diploma in Coding using python, PostgreSQL, and Flask.
- Troughout this project so far I have grown in confidence and feel like I can easily build a database from scratch, and also make it interactive for the user, something  I previously did not feel capable to do.
- From studying the course material and other resources on the web, I have learned lots of different ways to get the ideas from my head to the code of my database. It's been a thrilling ride!
 
## UX design

I wanted to make the user experience as easy to use but at the same time making the database unique and interesting to use. 

I created a number of HTML files in order that the finished project will be very interactive and fun to use.

The database allows for the creation, reading, updating and deletion of fantasy realms and cities. the cities are grouped according to their respective fantasy realms.

WireFrame

![Screenshots of the Wireframe](images/wireFrame.png "WireFrame")

On the About page - and Tours page - there is a form which the user can fill in and once they press Submit there is a Javascript function which validates whether the details have been entered correctly, if so a success message is posted on a popup as seen below.

![Screenshots of the Submitted PopUp](images/popup.png "Submitted PopUp")



## Bugs and Testing

I Manually tested the Fantasy Database every step of the way, using the web preview function on Gitpod. I also tested it once it was deployed on Heroku to check that it was still funtioning as I had initially expected it to.

I had a problem early on where I couldn't get PostgreSQL to work on Gitpod, I searched for a long time to find otu an answer to my problem, eventually I laded on Gitpod's own page where they showed me how to write the .gitpod.yml file which downloaded and installed PostgreSQL on the IDE.


JS Lint

Below is the result on JS Lint when I enter the Code from form.js:
![Screenshots of the JS Lint test of form.js](images/formJsLint.png "JS Lint - form.js")

And below is the result when I entered the code from quiz.js:
![Screenshots of the JS Lint test of quiz.js](images/quizJsLint.png "JS Lint - quiz.js")
3 Warnings were given, I spent some good time on stack overflow to see if other people had the same problem, and it seems like its a common occurrence and most people are saying it´s best just to ignore it, and seeing that it is a reqisite of p2.2 that i should have a loop, and also the wording saying there should be no "major" warnings I thought I could ignore it and put it down as a minor warning for the purpose of this excercise.

I have used a mixture of manual testing and automated testing in the creation of this website, the automated testing makes sure that it is in line with accepted standards, and the manual testing makes sure that it is comfortable for the user to use and has the correct level of interactivity.

W3 Validator
![Screenshots of the W3 test of HTML](images/W3ValidatorHTML.png "W3 Validation HTML")
I had a few trailing slashes which had no function but they are removed now.

Jigsaw CSS Validation
![Screenshots of the Jigsaw test of CSS](images/jigsaw.png "Jigsaw Validation CSS")
No issues found at all.

## Deployment
My site was deployed on Heroku at https://fantasy-database-93b7701d6f44.herokuapp.com/


## Credits
I used the Love Running project for inspiration including for the hero image inclusion and the responsiveness on smaler screened devices.
I drew inspiration from geeksforgeeks.org and sitepoint.com, for the quiz section of the website. 