Puppet-software-factory project (Work in progress...)
==================================================

Installation of a sofware factory with Maven, Jenkins, Nexus, and Sonar, driven by Puppet.
The virtual machine used for tests is managed by Vagrant and VeeWee

To clone the repo and the submodules :

    $git clone --recursive https://cliffmaury@github.com/cliffmaury/puppet-software-factory.git puppet-software-factory

Requirements
============

    - VirtualBox 4.1
    - Vagrant
    - VeeWee
    - ISO file of Ubuntu Lucid 32 bits (required for creating the base box, if needed)

Run
=============

    $vagrant up
    
Resources
========

    - http://puppetlabs.com
    - http://vagrantup.com/
    - https://github.com/jedi4ever/veewee
    - http://blog.aheritier.net/setup-your-devops-playground-with-puppet-vagrant-co/ (French)
    - http://blog.loof.fr/2011/10/puppet-vs-chef-fight.html (French)
    - http://binbash.fr/2011/08/28/puppet-apercu/ (French)