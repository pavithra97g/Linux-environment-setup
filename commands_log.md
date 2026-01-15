# Linux Environment Setup & Exploration -command log
##1: check current directory
pwd

##2: List files and directories

ls
ls -l

##3:Navigate directories

cd documents
pwd
cd ..

##4: create directories and files
 
mkdir rose
cd rose
touch sunflower.txt
ls

##5: remove files and directories

rm sunflower.txt
ls
rmdir rose

##6:view contents
nano sunflower.txt
```
Hey flower, how are you doing?
```
cat sunflower.txt
less sunflower.txt
tail -n 1sunflower.txt

###7: modify file permissions and ownership
sudo chown unni sunflower.txt
ls -l
sudo chown unni:unni sunflower.txt
ls -l
sudo chmod 776 sunflower.txt
ls -l

###8: system Monitoring
top
htop
df -h
free -m

###9 : Additional commands
whoami
sudo adduser unni
