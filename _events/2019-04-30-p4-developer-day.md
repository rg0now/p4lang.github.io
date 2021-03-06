---
layout: post
title: P4 Developer Day 2019
date: 2019-04-30
header-img: assets/p4-background.png
---

## A Presentation by the P4 Language Consortium  
#### *Held at Stanford University on Tuesday, April 30, 2019* 
## Special Thanks to our Sponsors:
<img src="/assets/cisco-logo.png" alt="Cisco" /> <img src="/assets/barefoot-logo.png" alt="Barefoot Networks" />  
&nbsp;

## Venue
#### Address: Arrillaga Alumni Center, 326 Galvez St, Stanford, CA 94305
#### Directions:
    
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3168.2722083658236!2d-122.16701278469225!3d37.43067377982362!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808fbb28416493a7%3A0x778a60994d7a5e4c!2sFrances+C.+Arrillaga+Alumni+Center!5e0!3m2!1sen!2sus!4v1526996941379" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>  

&nbsp;   
&nbsp;
&nbsp;

## Developer Day Tracks

New for this year, we are offering two tracks for the developer day: a
beginner track and an advanced track. Both tracks will be delivered by
experienced instructors and using a software platform that will be
made available shortly before the Developer Day itself.

&nbsp;

### <u>Beginner Track</u> 

This track is for developers who are new to P4 and want a
tutorial-style introduction to the languages main features. It is
organized around a series of programming exercises in which
participants implement conventional and novel solutions to various
problems in networking including:

* Basic forwarding, tunneling, and source routing
* Load balancing
* Monitoring and telemetry
* P4Runtime

Only basic programming knowledge is required, but familiarity with
Python and using a Linux virtual machines will be helpful. 

---

### Virtual Machine

We have created a VM with everything needed to work on the tutorial exercises, including the P4 Compiler, Behavioral Model, starter code, and editors. We suggest downloading the VM and executing the instructions below ***ahead of the tutorial.***

Use the following __[link](https://drive.google.com/uc?id=1lYF4NgFkYoRqtskdGTMxy3sXUV0jkMxo&export=download)__ to download the VM image (5.2 GB).

---

#### **Import and Run the VM**

The VM is in .ova format and has been created using VirtualBox. To run the VM you can use any modern virtualization system, although we recommend using VirtualBox. For instructions on how to get VirtualBox and import the VM, use the following links:

__[VirtualBox Download](https://www.virtualbox.org/wiki/Downloads)__

__[Importing a VM](https://docs.oracle.com/cd/E26217_01/E26796/html/qs-import-vm.html)__

Login Credentials *(To access the Ubuntu system in the VM, use the following credentials with sudo privileges):*
* User: p4
* Password: p4

---

#### **System Requirements**

The current configuration of the VM is 2 GB of RAM and 2 CPUs. These are the recommended minimum system requirements to complete the exercises. When imported, the VM takes approximately 8 GB of disk space. For the best experience, we recommend running the VM on a host system that has at least twice as many resources.
&nbsp;

---

### Agenda

<iframe src="/assets/P4WS_2019/P4D2_2019/Agenda, Beginner_Track.pdf" width="850" height="1100" frameborder="0" style="border:0" allowfullscreen></iframe> 

&nbsp;

---

### <u>Advanced Track</u> 

This track is for developers with intermediate knowledge of the P4
language. It is organized around a sequence of hands-on exercises that
show how to build a leaf-spine data center fabric based on Segment
Routing over IPv6 (SRv6), using the ONOS SDN controller:

* Basic forwarding
* Bridging
* SRv6
* ONOS Control Plane
* Testing in Mininet

Only basic knowledge of Java is required. The track will include a
brief introduction to ONOS for beginners. Participants will be
provided with a skeleton implementation of the applicationq to
complete, filling in the relevant parts to generate run-time table
entries and other entities to implement bridging and SRv6 capabilities. 

---

### Virtual Machine
We have created a VM with everything needed to work on the tutorial exercises, including ONOS, stratum_bmv2, Mininet, P4Runtime, PTF, and code editors. We suggest downloading the VM and executing the instructions below ***ahead of the tutorial.***

Use the following __[link](http://bit.ly/p4d2-spring19-adv-vm)__ to download the VM (5.3 GB). Please also make note of the backup __[link](http://bit.ly/p4d2-spring19-adv-vm-2)__.

---

#### **1.) Import and Run the VM**

The VM is in .ova format and has been created using VirtualBox v6.0.6. To run the VM you can use any modern virtualization system, although we recommend using VirtualBox. For instructions on how to get VirtualBox and import the VM, use the following links:

__[VirtualBox Download](https://www.virtualbox.org/wiki/Downloads)__

__[Importing a VM](https://docs.oracle.com/cd/E26217_01/E26796/html/qs-import-vm.html)__

Login Credentials *(To access the Ubuntu system in the VM, use the following credentials with sudo privileges):*
* User: sdn
* Password: rocks

---

#### * System Requirements

The current configuration of the VM is 4 GB of RAM and 4 core CPU. These are the recommended minimum system requirements to complete the exercises. When imported, the VM takes approx. 8 GB of HDD space. For a flawless experience, we recommend running the VM on a host system that has at least the double of resources.

---

#### **2.) Generate SSH Keys**

ONOS uses SSH key-based authentication to access its command line interface (CLI). Before using ONOS, you need to generate public/private rsa key pair using the following command inside the VM:

Command: ssh-keygen -t rsa -f ~/.ssh/id_rsa -P '' -q

---

### Agenda

<iframe src="/assets/P4WS_2019/P4D2_2019/Agenda, Advanced_Track.pdf" width="850" height="1100" frameborder="0" style="border:0" allowfullscreen></iframe> 

&nbsp;

### Instructors

* [Nate Foster](http://www.cs.cornell.edu/~jnfoster/) (Cornell University)
* [Brian O'Connor](linkedin.com/in/bocon) (Open Networking Foundation)
* [Carmelo Cascone](https://www.linkedin.com/in/carmelocascone/) (Open Networking Foundation)
* And others (TBA)
