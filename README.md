# linuxCmd

# sudo apt-get update

sudo apt-get install python3-pip

#swap 

df -h

sudo fallocate -1 8G /swapfile

sudo chmod 600 /swapfile

sudo mkswap /swapfile

sudo swapon /swapfile

sudo swapon --show

#screen

apt-get install screen

screen

screen -S name #creates a session with a name. name can be used to reattach at a later stage

screen -d SCREENID #when the command screen is running in another terminal, remote detach

screen -ls #it will list all the existing screen sessions

screen -r <SCREENID> #attaches to particular screen session
  
screen -r name #attaches to specific session (unique name specified during the creation of the screen session )

 CTRL-a k #it will ask "Really kill his window [y/n]". y for yes, n for no
 
screen -X -S SCREENID quit

screen -S SCREENID -X quit

