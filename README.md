# NetOps-LabTopo
Netops Automation Workshop Lab Information

Inside a box, is another box, and inside that box....


1. **Host machine:** Windows 10 on a Supermicro SuperServer E200-8D

1. **Virtualization/Hypervisor:**  VMware Workstation Pros 12.5.2

1. **NMS Station:** Ivan's (ipspace.net) NMS station built with Vagrant.

1. **Lab Environment:**  Just VIRL, for now.

1. **Lab Devices:** At the moment, a few NX-OSv devices and a NX-OSv 9K device.  

1. **Lab Topology:** Don't have one yet - devices are accessible via their mgmt interfaces - enough to do homework assignments week #1.  Will be building something out soon.


FWIW, I've been practicing the smaller concepts from Week 2 and Week 3 on our production network. :)  At the same time, in my daily job, terrible Python scripts (my college Pascal instructor would be apalled) is my crutch until Ansible becomes ingrained in my brain.

Also, I tried like mad to run Ubuntu on my Host Machine, but I just could not VMWare Workstation Pro 12.5 to play nice with the vagrant plugin and vagrant box.  Everything would install just fine, but there were a few problems with VMNet's disappearing both just within VMWare (after days, i did figure out a workaround for that) and then upon Vagrant-up of the NMS box.  I can provide even more detail for the curious.    
