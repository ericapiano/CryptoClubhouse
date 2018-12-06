# The Crypto Clubhouse
A NFL themed website that features sign up and login using a MySQL database to store usernames and passwords. The user will select their preferred NFL team and will be automatically sent to that team's page. They can also browse all 37 teams pages that use MySportsFeeds API and NewsApi to display updated division standing, game match ups and scroes, and team roster. There is a chat page that also uses a MySQL database for those signed in to send chats and respond to specific posts.


## Getting Started
* Clone repo
* Run `npm install` to install the required dependencies.

## Instructions
* From the command line, cd into repo "noteTaker"
* From the command line, run: heroku open
* Sign up by creating a user name and password and select your favorite NFL team (select 'all' if you are indifferent)
* At the notes page, the user will receive a form to fill out the "title" and "content" of their note. The user can hit the 'save' button, which will add the note to the bottom of the list of already submitted notes
* Each note added will gain a 'delete' button, which provides the user the ability to delete a note.


## Demo Link



## Technologies Used
* Node.js
* MYSQL NPM Package
* socket.io
* express
* sequelize 
* NewsAPI
* MySportsFeed API
* Sequel Pro
* Terminal
* Heroku
* datatables.net






SyneScribble
Check it out here: https://aarick-f.github.io/synescribble/

Georgia Tech Coding Bootcamp Fullstack Web Development Project 1

Team:
Aarick Farist
Michael Dibble
Lisa Huynh
Project Description
The purpose of this project is utilizing Paper.js and Firebase to create a dynamically updated community gallery of in-browser drawings. Paper.js allows a user to draw on the canvas element in HTML as point values. The drawing canvas is converted to an image and the data for it + the creator's name are stored in the Firebase database. The ColorAPI pulls rgb values that allow the users to choose which color to use when drawing. When the "Submit" button is clicked, the user's drawing is appended into the Gallery div, the data is pushed into Firebase and it is posted into Twitter with the use of the Twitter API and Codebird.

Project Sketches
API's and Technology
ColorAPI for pulling color options
Twitter API to post drawings into Twitter account
Codebird.js for handling automated posting to twitter
Paper.js for drawing
Bootstrap for extra styling and responsiveness
Firebase for persistent data storage
Who is doing what?
Aarick
Paper.js, Firebase interaction, Twitter API, Codebird implementation

Michael
Bootstrap implementation, HTML markup (Header + dynamically updating gallery images), CSS Styling

Lisa
The Color API Implementation, HTML markup (footer + dynamically generating color squares), CSS styling