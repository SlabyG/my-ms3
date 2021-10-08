Technology used:

1. RandomKeygen https://randomkeygen.com/ - Fort Knox Passwords to generate secret key
2. Materialize https://materializecss.com/- Used for css and styling 


Deployment on Heroku:

1. Create account on Heroku. 
2. After creating the account login.
3. Click on New (top right corner) and select new app
4. enter app name using lower case letters and mix of underscores or dash line/minus and select Region(ie.Europe)
5. Click on Create App
6. For this exercise i have connected my repo to the GitHub, by entering my repo name and then clicked Connect
7. Go to settings on top right corner and click on on Reveal Config Vars to instruct Herokuwich vaariables are requiered
8. After updating all the variables go back and click Deploy to push the new files to the repositories
9. Go to the automatic deploys and click Enable Automatic Deploys 
10. Go to Manual deploy and click Deploy Branch (meantime heroku will recive the code from GitHub)
11. After received you will notice an alert saing "Your app was successfully deployed" and will give you a button to View the app
12. When clicked on it the app should open in the browser providing you with a secured link ie (https://flask-mythirdb-project.herokuapp.com/)