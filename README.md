spree-vagrant
=============

vagrant repo for spree developmemt

Use aws provider for Vagrant - https://github.com/mitchellh/vagrant-aws

After installing vagrant and chef, run the following commands:


add a dummy box
```shell
vagrant box add dummy https://github.com/mitchellh/vagrant-aws/raw/master/dummy.box
```

```shell
git submodule update --init
vagrant up
```

After the VM is up and running, run:

```shell
vagrant ssh
```

to ssh to the VM and install rails:

```shell
gem install rails -v 4.0.0
gem install therubyracer
```
