ansible-play book will perform following tasks:

1: It will provision EC2 Instance 

2: Launch instance with keyname: virginia ( must be created first )

3: Assign security group to instance ( already created ) name can be anything.

4: It will launch instance in North Virginia ( us-east-1 ) region

5: Instance type: can by anything you want.

6: Provide valid ami to launch instance with that ami.

7: Provide valid subnet ID in order to launch an instance in that particular subnet.

8: exact_count= is the limit of instance you want to launch at once.

9: It will give tag name Demo to instance ( launched )

10: it will auto assign public ip to instance


root@linuxguy:-# ansible-playbook ec2.yml
