Getting started
---------------

* Install [Vagrant](http://vagrantup.com),
  [Fabric](http://fabric.readthedocs.org/en/latest/installation.html),
  and [fabtools](http://fabtools.readthedocs.org/en/latest/).

* Change config.ini to have your project name (currently called FabTools_StartKit)

* From the command line, run `fab dev vagrant.up provision`. This will
  create a virtual machine with all the necessary packages.

* SSH to the virtual machine with `vagrant ssh $(Your Project Name)`

* Put in any python or other unix tools you want in REQUIREMENTS or REQUIREMENTS-DEB