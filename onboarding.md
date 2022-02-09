# Shell scipting-onboarding new users

Create direcotry shell

`mkdir Shell`

![](images/1.png)

In shell directory, create a file names.csv 

`vim names.csv`

![](images/2.png)

Add list of new users
![](images/3.png)

Create a group named developers

`sudo groupadd developers`

![](images/4.png)

Create shell-script and add code

`vim onboard.sh`

![](images/5.png)

make onboard.sh an executable 

`sudo chmod +x onboard.sh`

In .ssh directory, create a file id_rsa.pub

`vim id_rsa.pub`

![](images/6.png)

in .ssh directory, create a file id_rsa

`vim id_rsa`

![](images/7.png)

run onboard.sh 

`./onboard.sh`

![](images/8.png)

run onboard.sh in root user

`sudo su`

![](images/9.png)

`sudo ./onboard.sh`

![](images/10.png)

![](images/11.png)

Check users created

`ls -l /home/  `
![](images/12.png)

## connecting to user from a new terminal

create pem file

`vim auxproject.pem`

![](images/15.png)

run ssh

`ssh -i auxproject.pem username@ip-addresss

![](images/17.png)