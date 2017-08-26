# Description 

For the [VMWorld 2017 Hack-a-thon](https://blogs.vmware.com/code/2017/07/28/vmworld-hackathon-back/), we wanted to do something cool with [Ansible](https://www.ansible.com/).  Given the length of time and the co-captain's love for infrastructure, we decided to tackle Vsphere lab environment deployment and configuration using Ansible.  [Virtuallyghetto.com](http://www.virtuallyghetto.com/) has some great utilities for the Windows and Linux community, but the flagship seems to be the PowerCLI nested deployments.  I think that we can build the same functionality with Ansible, and hopefully provide a repo with the same feature functionality as the PowerCLI deployment script.  

# Goals 

1. Deploy a nested lab environemnt without using PowerCLI.
2. Deploy the infrastructure in less than 50 minutes.  
3. Deploy a web, middle, and db infrastructure.

# Developer laptop requirements 

These requirements are intentionally loose, because there are a number of approaches and helper tools that we can use to tackle this problem.

* GitHub account 
* Git push and pull software for your laptop 
* Text Editor
* Use Ansible

If we are lucky we could have some feedback for the Ansible community and the beginnings of a quick and easy deployment tool for your VMware lab environment needs.



