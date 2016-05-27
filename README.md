# AutomationWorkshop
Files related to the Juniper Automation Workshop

PDF copy of the slide presentation for the Workshop is included here.
Additional files provide what is needed to do the Juniper Automation Workshop lab exercices. Functionality has been verified
26 May 2016.

Software requirements for running the lab:
Windows:
Git: https://www.git-scm.com/downloads
  Install with utilities added to PATH environment, this allows the 'vagrant ssh host' command to work
  as git provides an ssh executable that the vagrant command can find
Vagrant: https://www.vagrantup.com/downloads.html
Virtualbox: https://virtualbox.org/wiki/Downloads

Mac OSX:
Install Vagrant and Virtualbox. OSX has ssh included with the OS


Running the lab:
Download the files and from shell or dos prompt cd to the lab directory and then issue 'vagrant up' 
to start the virtual machines (ubuntu and vsrx).

If you were present at the Workshop at Juniper's Bridgewater NJ offices on 19 May 2016, the only thing you need to get 
a copy of is the VagrantFile to run the lab. There was an underlying package dependancy change that was missed and 
caused the connection errors.
To update your lab, download the VagrantFile from here and place it in you lab directory, then from the shell 
or dos prompt issue the following two commands:
vagrant destroy ubuntu
vagrant up
