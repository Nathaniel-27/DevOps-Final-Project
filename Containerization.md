# What I have learned about Containerization.md
### I learned that containerization is a powerful tool for developing web apps as you can update and work on certain parts of your site instead of having to try to run the whole site and updating one part of the site you can instead turn that part into a container in docker to make work easier and I learned some commands that I will list below
## some useful docker commands I learned from contatinerization
1. docker ps  This command allows you to check the containers you have created
2. docker ps -a  Which is almost the same as docker ps but it shows you all your conntainers all that are up and down unlike docker ps which is just the containers that are up and running
3. docker run -d -p 8080:80 nginx this command is what tells docker to run your container the -d means you will run the container detached and the -p means your mapping a port to it like 8080:80 nginx
4. docker start -it this command allows you to enter your container as long as its up and running 
5. echo allows you to create a file inside the container and this is an example of the command: echo “Your text here!” > /tmp/[insertfilename].txt