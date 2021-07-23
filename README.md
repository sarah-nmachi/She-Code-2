# She-Code-2
Below were steps taken to achieve Task num 1:

##step 1 - Preparation of my environment. 
For this task, I created an Azure account. To create an azure account visit  portal.azure.com. 
Created a Linux virtual machine to host my Jenkins. Added an inbound port rule 8080 and also made my IP address static (20.86.110.254)
Created a Docker account for deployment which will be discussed later.

##step 2 -  Jenkins Setup
A prerequisite for installing Jenkins is the installation of Java. After connecting to the Linux VM. I installed Java
Install Jenkins on the Virtual machine, started the development server, and created an administrative user. Username:  Password: 
Installed Suggested Plugins

##step 3 - Create a build Job
Created a build Job named SCA cloud 1
Used a Declarative Pipeline syntax by creating a Jenkins file in my Github repo.
Installed a nodejs plugin in my Jenkins server as my app is running using NodeJS, also, the tool used in the Jenkins fine is a nodejs tool.
Added my Github Credentials and integrated my repro successfully to Jenkins as seen below.
##step 4 - Deployment
Create a repository in the Docker account created from step 1
Created a Docker file in my Github 
Installed a Docker Plugin in my Jenkins server
Installed Docker also in my Linux VM
Then Build again as seen in the below screenshot.
##Notes
Username
Password
Jenkins Url
If the server isn't available, that means my azure credit finished before the assessment. Do not hesitate to contact me at onyinyeonomesky@gmail.com

##Ref
https://www.digitalocean.com/community/tutorials/how-to-install-jenkins-on-ubuntu-20-04
https://www.jenkins.io/doc/book/pipeline/syntax/
https://docs.cloudbees.com/docs/admin-resources/latest/pipeline-syntax-reference-guide/declarative-pipeline
https://docs.docker.com/engine/install/ubuntu/


