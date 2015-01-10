UPPNEX15 VM - Nextflow 
======================

Virtual machine for the Nextflow tutorial

Prerequisites 
---------------

This project contains a Vagrant configuration file 

In order to use it, you will need to install the following pieces of software: 

* Virtual Box (suggest version 4.3.12) https://www.virtualbox.org/wiki/Downloads
* Vagrant (version 1.5 or greatet) http://www.vagrantup.com/downloads.html


Setup 
--------

To Clone the UPPNEX15 virtual machine, you have
Clone the UPPNEX15 virtual machine (this project) in a convenient location by using the command:

    $ git clone https://github.com/nextflow-io/UPPNEX15-vm.git


Change to the `UPPNEX15-vm` folder and launch vagrant:
    
    $ cd UPPNEX15-vm/
    $ vagrant up  
    

The first time you run it, it will automatically download the virtual machine required by the tutorial. 
It may take some minutes to complete, so be patient. 

When it boots up and the configuration steps are terminated, login into the VM instance:

    $ vagrant ssh 
    
You are now in the virtual machine. Now you can verify that Nextflow is working by entering the command: 

    $ nextflow -version 


