bootstrap
=========

Generic virtual machines with a bootstrap for working with open source projects.  

Use Vagrant to get up and running with an ubuntu 12.04 with JDK 7   

1) Install Vagrant [http://www.vagrantup.com/](http://www.vagrantup.com/)  
2) Install Virtual Box [https://www.virtualbox.org/](https://www.virtualbox.org/)  

    git clone https://github.com/stealthly/bootstrap.git
    cd bootstrap
    vagrant up
    vagrant ssh

The ubuntu virtual machine will be running on 192.168.95.75 and anything you bind to that ip within the instance will be accesible from your local machine.
