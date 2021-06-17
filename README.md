# CICD with Jenkins

## Why Jenkins?
Multi Billion Dollar companies like Facebook, Netflix and Ebay have adapted Jenkins because of it’s amazing advantages, Jenkins is an open-source automation server in which the central build and CI process take place, It is a Java-based program with packages for Windows, macOS, & Linux.

![](jenkins.png)

- set up Jenkins
- create accounts/login to Jenkins 
- create our first job
- Automated Testing on Jenkins Agent Node

![](CICD.png)

### Setting up ssh connection between Git-hub and Jenkins
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