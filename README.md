# pipeline-learn
learn aws CI/CD pipeline


EC2 Script

#!/bin/bash
sudo yum -y update
sudo yum -y install ruby
sudo the yum -y install wget
cd home/tilangaaws2
wget https://aws-codedeploy-us-east-2.s3.amazonaws.com/latest/install
sudo chmod +x ./install
sudo ./install auto

Check if Codedeploy agent is runing:

sudo service codedeploy-agent status

Code Deploy logs
