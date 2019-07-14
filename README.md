# FriendFinder

## What it is
FriendFinder is a full-stack site that pairs users to their "companion" based off of their survey answers. 
<br>This application specifically uses **Node** and **Express**. You can find the deployed **Heroku** link below:
<br>https://evening-island-42544.herokuapp.com/

## How it was made
- Proper **Node** installation and modules, do the following in the terminal: "npm init -y", "npm i express", "npm i path"
- The app was divided into multiple files and folders; they were then accessed through **Express** and **Path**
- Using Express in server.js, I was able to create a server with proper routing for my application to work properly
- My routing javascript files set the default landing zone for when the user goes to the first page and where the user 
would be rerouted when they include /survey at the end of the link or if they were to click on the survey button
- Inside the public folder were my **html** files, the pages to be displayed. I didn't have a seperate css file but rather 
just used **bootstrap** within the html files. **Javascript** and **jQuery** was also used. 
- The friends.js file in my data folder was where our friends array was stored (name, pic url, survey answers)
- The apiRoutes.js was the logic necessary for the survey to record the user's information to my array and then use that 
same data to find the closest fit by finding the person with the lowest total difference in survey answers

## How it works
Two ways:
1. clone this repository
  - open the terminal where you cloned the repository and then go "npm init -y", "npm i express", and "npm i path"
  - then do "node server.js", which will the launch the server
  - open your default browser and type in the url "localhost:3000"
  - you will see an introduction page with a button to continue
  - once you hit the button you will end up on a survey page
  - fill out the information and submit, and a modal will pop up with your friend!
2. go to the deployed version of this app: https://evening-island-42544.herokuapp.com/
   - you will see an introduction page with a button to continue
  - once you hit the button you will end up on a survey page
  - fill out the information and submit, and a modal will pop up with your friend!

## Screenshots of working app
<br>![pageOne image](https://github.com/birnapwnsu/FriendFinder/blob/master/screenshots/pageOne.JPG?raw=true)
<br>![pageTwoA image](https://github.com/birnapwnsu/FriendFinder/blob/master/screenshots/pageTwoA.JPG?raw=true)
<br>![pageTwoB image](https://github.com/birnapwnsu/FriendFinder/blob/master/screenshots/pageTwoB.JPG?raw=true)
<br>![Modal image](https://github.com/birnapwnsu/FriendFinder/blob/master/screenshots/Modal.JPG?raw=true)
