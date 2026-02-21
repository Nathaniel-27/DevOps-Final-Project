# What I learned about Version Control
Version control is highly important as you dont wanna use just one version of your project or web app. Using version control with github allows you to work on stuff with out worrying about ruining the main code as it allows you to work on branches that have to be pushed and need to be reviewd either by a human or an automaton script before they are accepted and merged the best uses of this are so you can revert to older versions if you mess up the current version it also allows lots of people to work on as it uses repo clones. 

# Version control commands I learned in Dev Ops
1. Git add . will stage all files before commiting
2. Git commit -m "Example message" Will commit the files and you will always need to include a message when you commit
3. Git push origin branch main will push your branch to Git hub 
4. Git pull origin main will download the latest changes from github
5. Git branch {name of branch} this will create a new branch that you can then work from 
6. Git checkout feature-name OR git switch feature-name allows you to switch branches easily provided you spell the name correctly
7. Git Status allows you to quickly what branch you are working in
8. Git checkout master or main When you are ready to bring your changes back to the main branch this is the command youll use 
9. Git merge feature-name This will create a merge request locally that you can then accept and merge 
   If you want to add collaborators you will need to first be on github and in your repo and then go to Settings --> collaborators --> add  people and then add them via there Github username, email, or name and it then it will send them a usally an email they need to accept
 10. git clone {repo url} this is the command you will use to clone a repo weather your working inside your own or a collaborator of someone elses
