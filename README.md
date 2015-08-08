<h2>Vagrant and Puppet configuration for NodeJS</h2>

Vagrant configuration with puppet to create a Virtual Box machine with 
Ubuntu Server 14.04 with Nodejs




**installation:**

* Install Vagrant
* Install Virtual
* Clone the repository git clone [git://github.com/KarlPurk/vagrant-nodejs.git](git://github.com/KarlPurk/vagrant-nodejs.git)


**running:**

* Run - vagrant up<br>
* SSH - vagrant ssh<br>
* Halt - vagrant halt<br>




**development:**

by default this vagrantfile have this configuration for shared folder between the host and the VM
*[config.vm.synced_folder "~/", "/vagrant"](https://github.com/KarlPurk/vagrant-nodejs/blob/master/Vagrantfile#L25)*



**Puppet Manifest will install:**

* [n](https://github.com/visionmedia/n) a node.js version management
* wget
* git
* vim htop
* g++



Good hacking!!!!!!!!
