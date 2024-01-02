# Module 1 - Deployment
![Module1-Deployment](https://github.com/cyz-do/Exercise-Cloud-Deployment/assets/93310239/557fce23-9623-48fe-bea6-8d4edf41028b)

The static HTML website is hosted on AWS EC2, utilizing the Apache HTTP server on port 80.

URL: ec2-18-141-172-26.ap-southeast-1.compute.amazonaws.com:80


# Module 2 - Continuous Deployment
![Module2-ContinuousDeployment](https://github.com/cyz-do/Exercise-Cloud-Deployment/assets/93310239/a1a68187-f097-407b-bcbb-4272190eb55e)

After changes are committed to the default branch on GitHub, the deployment script, utilizing ssh-deploy, pushes the changes to the target directory hosting the website (/var/www/html).
