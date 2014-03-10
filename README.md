PROJECT
=======

### Setting up the development environment

#### First time

##### Install prerequisites

  vagrant
  virtual box

##### Launching VM and SSH

  if windows install git for using SSH
  cd vagrant
  vagrant up
  vagrant ssh

###### Within the virtual machine
  apt-get install curl
  \curl -sSL https://get.rvm.io | bash  (RVM for manage rubies environments) [More information](http://rvm.io/rvm/install)
  rvm install ruby 2.0.0-p247

  cd /project
  bundle install
  rails server

##### Open your browser (your computer!!)
  localhost:300
