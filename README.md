A03 Personal Website
A simple website using server-side:

Node.js platform
Express web framework
Morgan HTTP request logger
Body-Parser to automatically parse HTTP request bodies
NodeMailer for emailing contact form information
Nodemon for live updates
nconf to keep authorization information in a config.json file (not committed to repo)
MailGun (10,000 free emails)
and client-side:

BootStrap framework for responsiveness & styling
Initializr from http://www.initializr.com/
Links
Code Repository
Demo
Development Tools
Windows Explorer Context Menu: Add 'Open command window here as administrator' http://www.sevenforums.com/tutorials/47415-open-command-window-here-administrator.html
Visual Studio Code
Get Started
Open a command window in your c:\44563\a03 folder or from VS Code menu, chose View / Integrated Terminal
Install nodemon globally with npm install -g nodemon
Install the dependencies listed in package.json with npm install.
Run nodemon to start the server. (Hit CTRL-C to stop.)
> npm install -g nodemon
> npm install
> nodemon
Open browser http://localhost:8081.

Set up Mailgun
Sign up for an account at https://www.mailgun.com.
Log in.
Go to your dashboard athttps://app.mailgun.com/app/dashboard.
Scroll down to get your "Domain Name".
On the right, click the eye to view your private API key.
Create a new config.json from the config.json.example.
Set your domain name and private api key as found above.
Add your private config.json to the .gitignore file.
Deploy to Heroku Free Hosting
Register for a free Heroku account at https://www.heroku.com/.
Download and install Heroku CLK https://devcenter.heroku.com/articles/heroku-cli.
Log in to your Heroku cloud account.
From your dashboard, click New and add a new project.
Click the new project and click the Deploy tab.
Click 'Open app' to run your app and view the Heroku URL in the browser.
Open a Windows Command Window as Administrator, and run 'heroku login'.
Open Git Bash in your project folder, add the heroku remote (Command 1 below).
In Git Bash, push to your heroku remote (Command 2 below).
git remote add heroku https://git.heroku.com/resumesite563.git
git push heroku master