# Simple Riak Vagrant Cluster

This is a Vagrant project using shell-script provisioning to bring up a local [Riak](https://github.com/basho/riak) cluster. Each node runs 
`CentOS 6.5` 64-bit with `1024MB` of RAM by default.

## Configuration

### Install Vagrant

Download and install Vagrant via the
[Vagrant installer](http://downloads.vagrantup.com/).


### Clone repository

``` bash
$ git clone https://github.com/angrycub/simple-riak-cluster.git
$ cd simple_riakcs_vagrant
```

### Launch cluster

``` bash
$ vagrant up
```

## Contribution

Community supported repos survive because of community contribution. Here’s how to get started.

* Fork the appropriate sub-projects that are affected by your change
* Create a topic branch for your change and checkout that branch
     `git checkout -b some-topic-branch`
* Make your changes and run the test suite if one is provided (see below)
* Commit your changes and push them to your fork
* Open a pull request with a descriptive title
* Maintainers will review your pull request, suggest changes, and merge it when it’s ready and/or offer feedback
* To report a bug or issue, please open a new issue against this repository

You can [read my favorite guidelines for bug reporting and code contributions](http://docs.basho.com/riak/latest/community/bugs/) on the Riak Docs. And **thank you!** Your contribution is incredible important.
