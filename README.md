# DemoWebApp


A personal website created in Hubspot's annual Women in CS workshop for college
students interested in CS. This project was forked from a project
by Zoe Sobin, which can be found at https://github.com/zsobin/DemoWebApp.git.

To set up and run:

1. Make a copy of my existing project on github
  - Fork the project at https://github.com/cathyc96/DemoWebApp.git

2. Bring your new copy onto your computer from github
  - `cd ~/Desktop`
  - `git clone https://github.com/YourUserName/DemoWebApp.git`
  - `cd DemoWebApp`
  - `ls`

3. Initialize it as a heroku project
  - `heroku login`
  - `heroku create`

4. Send the heroku project to heroku’s servers and view it online
  - `git push heroku master`
  - `heroku open`

5. Install the project’s dependencies and run the project on your local servers
  - `npm install`
  - `heroku local web`
  - check out http://localhost:5000
