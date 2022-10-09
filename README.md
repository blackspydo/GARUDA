# GARUDA

 ----
 ## Go-lang installation 
     sudo apt-get remove -y golang-go
     sudo rm -rf /usr/local/go
     wget https://go.dev/dl/go1.19.1.linux-amd64.tar.gz
     sudo tar -xvf go1.19.1.linux-amd64.tar.gz
     sudo mv go /usr/local
     nano /etc/profile or .profile
     export GOPATH=$HOME/go
     export PATH=$PATH:/usr/local/go/bin
     export PATH=$PATH:$GOPATH/bin 
     source /etc/profile #to update you shell dont worry
     
     
----
## How to install

    git https://github.com/blackspydo/GARUDA.git
	cd GARUDA
	sudo chmod +x garud.sh
	sudo ./garud.sh


