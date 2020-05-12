# Chef Pi
This is the bootstrap script and chef files needed to run chef-solo on a new Rasberry Pi system to get it setup and ready. 

# Bootstrap
This bootstrap script is needed to get the sytem updated and all the supporting libraries, etc. to get chef-solo to run. The script will run chef at the end and reboot the box. 

`curl -L https://raw.githubusercontent.com/ryanspaulding/chef-cm/master/bootstrap.sh | bash`

# Last Steps
Set the password for all accounts b/c they are empty by default. 
