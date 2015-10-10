# I guess this is a distribution of DCOS?  

### What's inside: 

 * build scripts for arch linux images that turn a plain netboot into: 
  * For control nodes: 
   * git-current mesos + marathon + zookeeper for control nodes
   * stable mesos + marathon + zookeeper for server nodes
  * For servers:
   * git-current mesos-slave
   * stable mesos-slave
   
We're working on [Pixiecore(https://github.com/danderson/pixiecore)] to create a sequential automatic provisioning tool released as 100% open source hardware and software.

We owe a debt of gratitude to all of the open source developers who enabled this project for us.  If you contributed, you enabled, and we thank you.    