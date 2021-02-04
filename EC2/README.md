### EC2 AWS Commands

**Launching the EC2 install with Script**

>> aws ec2 run-instances --image-id "ami-id" --instance-type "t2.micro" --key-name "key_name" --security-groups "SG_name" --user-data file://script.txt
