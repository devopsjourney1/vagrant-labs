# Ansible Labs

These are Vagrant Labs for the youtube Channel DevOps Journey.

Each folder corrasponds to a video. Follow along and let's learn Vagrant together.

## How to use these Labs
1. Install Vagrant: https://www.vagrantup.com/downloads.html

2. Install Oracle Virtual Box:  https://www.virtualbox.org/

3. In a new Directory copy this respository:
``` shell
git clone https://github.com/bradmorg/vagrant-labs.git
```
4. go into the lab folder corrasponding to the video you are watching
``` shell
cd lab1-firstvm
```
5. Initialize the VM using vagrant init
``` shell
vagrant init bento/ubuntu-18.04
```
6. SSH into the VM

``` shell
vagrant ssh
```