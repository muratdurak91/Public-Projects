# Linux Project 04 : String Manipulation

You are working in Healthcare Company as DevOps engineer. Recently, you have been assigned some tasks by your manager. This part has 3 different tasks. Please follow the problem statements. 

### Task 1: 
You are writing an ansible playbook file and an ec2 instance is created one part of it. Than you have a description file named `info.json` belonging to newly created ec2 instance. Some steps later, to be able to create a git repository with `terraform.tf` file, you need to pass private IP of newly created ec2 instance to environmental variable which is `ec2_private_ip` on the line 40. You must not open `terraform.tf` file and paste the IP taken from `info.json` in related part. You have to do all those acts with linux commands and you must not open terraform and json files. Please take the private IP of EC2 instance from ec2 description file (`info.json`) and change the `ec2_private_ip` value with it within `terraform.tf` file. 


### Task 2:
Again you are writing an Ansible playbook file. In one part of that file, a pem key is created and app gives you that file one line format like `certificate.pem`. You have to turn it into multi line format to use it in another place of ansible file. Please get that `certificate.pem` one line pem key file and create and copy its multiline format in `new.pem` file. 

### Task 3: 

You have audit log file which has ssh connection logs to your server. However some invalid users try to connect your system. You have been assigned a task to find their names and how many times have they tried to attack your system. Please find it and put it into the `invalid_user.sh`file.

## Project Skeleton 

```
Linux_Projects (folder)

|----String Manipulation
|--------Task_1
|------------info.json            # Given to the DevOps
|------------terraform.tf         # Given to the DevOps
|------------command.sh           # To be delivered by DevOps  
|--------Task_2
|------------certificate.pem      # Given to the DevOps
|------------new.pem              # To be delivered by DevOps
|------------command.sh
|--------Task_3                   
|------------auth.log             # Given to the DevOps
|------------invalid_user.sh      # To be delivered by DevOps
```