# How to set up server

## Stacks

Linux(Ver: AWS VM Ubuntu 20.04.2 LTS, UsedTo: Server computer)
Windows(Ver: 10 Home, UsedTo: Local computer)
MobaXterm(Ver: Personal Edition v21.4, UsedTo: Connect server and local via SSH and SFTP)

## 1. Make a virtual machine

* [Create a new aws account](https://aws.amazon.com/ko/free/)
* *(optional)* [Make admin account with IAM](https://console.aws.amazon.com/iam/home) ([more details on here](https://extsdd.tistory.com/76?category=853192))
* [Make EC2 instance with key pairing](https://ap-northeast-2.console.aws.amazon.com/ec2/v2/home?region=ap-northeast-2#LaunchInstanceWizard:)
* *(optional)* [Make elastic ip adress](https://ap-northeast-2.console.aws.amazon.com/ec2/v2/home?region=ap-northeast-2#Addresses:)

## 2. Connect your computer(local) with VM(server)

* [Download MobaXterm](https://mobaxterm.mobatek.net/download.html)
* Make SSH session and add ip address and private key with pem extension
* Type `ubuntu`(default user name) to enter VM(Type `exit` to exit)

## 3. Set your server

* Set root password with typing `sudo passwd root` commend
* s

## 4. Make vertual invironment

*
