Hello, this is my GIT tutorial
1. Configure my github account on my computer
2. Establish an ssh connection 
$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
enter to place ssh into default location, and enter a password
2. Add the ssh to my github
$ clip < ~/.ssh/id_rsa.pub # copies the keys to clipboard
3. Test ssh connection
$ ssh -T git@github.com
continue to connect (yes)

work on the file 

4. git add . || git add FILENAME # add specific file to staging area
5. git status # return list of things to commit
6. git commit -m "Commit message"
7. git remote add origin git@github.com:loshxhs1412/myproject #adds myproject to the name origin
8. git remote -v #list remote connections
9. git push -u origin master #pushes changes to origin

10. git diff #shows the file changes not yet staged