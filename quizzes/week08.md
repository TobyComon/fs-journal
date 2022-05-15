# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
It is the file that enables NPM to start the project, and install dependencies
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
In the root directory. Since this is where Heroku checks for the file to determine that it is Node.js
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
the .env and ENV.js files?
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
You can view logs in the CLI by running heroku logs --tail  or the dashboard. 
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Add the files to the local Git repo, commit the changes, then run git push heroku main
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
It is important so that you hopefully avoid merge conflicts
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
After tests have been completed. 
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging
```