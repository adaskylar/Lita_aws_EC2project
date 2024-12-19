# Lita_aws_EC2project
The project shows the process used to launch an EC2 instance and deloy Apache.
### Security Group Creation
Using an existing vpc and subnet i went on to create a security group. 

Named security group, I went on to set the inbound rule allowing SSH and HTTP traffic. 
### Instance Creation
Named instance, chose the desired AMI
![AMI](https://github.com/adaskylar/Lita_aws_EC2project/blob/main/AMI.PNG)
Chose the t2 micro (instance type). I created a key pair and inputted it.
Edited the VPC changed the subne to public to enable it viewed over the internet
Inputted security group and went on to create instance.
![InstanceInIt(https://github.com/adaskylar/Lita_aws_EC2project/blob/main/InstanceInIt.PNG)
![InstanceDetails(https://github.com/adaskylar/Lita_aws_EC2project/blob/main/InstanceDetails.PNG)
### Connect to Apache Web Server
Opened SSH Client, 
![ConnectSSHClient(https://github.com/adaskylar/Lita_aws_EC2project/blob/main/ConnectSSHClient.PNG)
went to command line to call up my files
Went on to install apache using the commands
![InstanceSSH(https://github.com/adaskylar/Lita_aws_EC2project/blob/main/InstanceSSH.PNG)
![Installapache(https://github.com/adaskylar/Lita_aws_EC2project/blob/main/Installapache.PNG)
![Confirmingru(https://github.com/adaskylar/Lita_aws_EC2project/blob/main/Confirmingru.PNG)
![sshexit(https://github.com/adaskylar/Lita_aws_EC2project/blob/main/sshexit.PNG)


