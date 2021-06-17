# CICD with Jenkins
![](CICD.png)

- set up Jenkins
- create accounts/login to Jenkins 
- create our first job
### setting up ssh connection between Git-hub and Jenkins
- Generate new ssh key in your localhost/laptop and name it yournamejenkins
- copy public ssh key into github the .pub file yournamejenkins.pub
- copy private ssh key into Jenkins - yournamejenkins
- add https git-hub repo url in the git project
- add ssh git-hub url into repository URL after select Git underneath source code management
- change the branch to main 
- execute shell
```
cd app
npm install
npm test
```
- save and trigger the build