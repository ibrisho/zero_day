  # Vagrant
    This Repo is about setting up VM on Ubuntu using vagrant
  ## Installing Ubuntu 20.04 VM on Linux

  * Open the Terminal application:
    * Now you will execute command line in your Terminal (each of them start with $)
  * Install VirtualBox: $ sudo apt-get install virtualbox
  * Install Vagrant: $ sudo apt-get install vagrant
  * Add the **Ubuntu 20.04 (Focal)** image to your box list: $ vagrant box add ubunt  u/  focal64 **Warning: this step can take time**
    * Many other images are available [here](https://app.vagrantup.com/boxes/search "here")
  * Create your first virtual machine:
    * $ vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "  ubuntu/focal64" - *you don’t have to execute this command line everyday, only   once, to create a new virtual machine*
    * $ vagrant up -> it will start your virtual machine
    * $ vagrant ssh -> now you are inside your virtual machine.