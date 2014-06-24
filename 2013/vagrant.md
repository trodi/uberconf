vagrant
=======

* infrastructure as code
* automate workflows
* great documentation 
* mount code folder in vm
* put your vagrant box in artifactory?
* can have vagrant point to puppet master as well to get central updates
* multiple machine config in single vagrant config
* puppet's lang forces the correct declarative style etc, chef is a ruby DSL and you can go cray cray
* jenkins vagrant plugin -> can CI the env | _*out of date*_, relies on older version of vagrant

### us...
* could do fresh installs of product for QA...

### resources
* vagrantbox.es
* varantup.com

### support
* virtural box (can also do vagrant package to create a base box from current)
* fusion
* vmware workstation

packer
------
packer.io
create identical machine images for multiple platforms

1. install vagrant
2. dl a base box
3. vagrant add
4. vagrant init 
5. vagrant up

workflows
---------
* create sandboxes
* get a new dev up and running
* production like environment
* disposable integration env
* FUTURE - production deployment (basic deploy to aws exists, maybe rackspace and vsphere)

### questions
* why is this better than something like boxen?
* installing paid software that requires keys etc? (can you pass in cmd params?)
* can you switch an existing box from virtual box to vmware workstation?
> need different basebox, have to do 'vagrant up' with new provider