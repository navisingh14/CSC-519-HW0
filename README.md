# CSC-519-HW0

### Name:                                                          
Navjot Singh 

### Student Id:
200154743
### Unity Id: 
nsingh9@ncsu.edu

#### Slack Profile Link: 
https://csc519-spring2018.slack.com/team/nsingh9
![Flow Chart](slack.PNG)


#### Moodle Profile Link: 
https://moodle-courses1718.wolfware.ncsu.edu/user/profile.php?id=100604

![Flow Chart](moodle.png)


#### Vagrant File
[Click here to go to the vagrant file](https://github.ncsu.edu/nsingh9/CSC-519-HW0/blob/master/Vagrantfile)

#### Post-receive file
[Click here to go to the post-receive file](https://github.ncsu.edu/nsingh9/CSC-519-HW0/blob/master/post-receive)

#### Post-commit file
[Click here to go to the post-commit file](https://github.ncsu.edu/nsingh9/CSC-519-HW0/blob/master/post-commit)

#### Hook Script
```shell
#!/bin/sh
sensible-browser https://www.youtube.com/
exit 0
```


#### Screencast link:
[Click here to watch the video](https://www.youtube.com/watch?v=BRO5zzdeZoM)  
00:00 Computing workshop - sync folder  
1:37 Hook script  
2:45 Simple pipeline  

#### Ques. What else could you use hooks for? What might you want to do before pushing changes to production?
Answer. These could also be used to notify other members when a new change has been pushed if they are waiting on a work to be done. Before pushing the changes to the production we might want to check things like code coverage and test coverage to see if any changes highly affected them.
