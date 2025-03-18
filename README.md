# Deploy_AWS_Hello

This is basic how to heploy hello world to aws ec2


1) be in the folder where .pem file is there and try to connect to running ec2 instance  :
ssh -i "deployment_aws.pem" ubuntu@ec2-13-51-146-199.eu-north-1.compute.amazonaws.com

2) type yes

3) ls

4) open new cmd now connect via sftp to put and get files from aws ec2 instance
sftp -i "deployment_aws.pem" ubuntu@ec2-13-51-146-199.eu-north-1.compute.amazonaws.com

5) put your zipped file and its name aws
put deploy_hello deplo_aws

6) now go to ssh connection
sudo apt update

7)sudo apt install python3

8)flask --version

9)python3 --version

10)sudo apt install python3-joblib
sudo apt install python3-flask
sudo apt install python3-sklearn

11)sudo apt install unzip
unzip --version

13)
