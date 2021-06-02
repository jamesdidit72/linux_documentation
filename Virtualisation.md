```
Application             App  App  App
                        os   os   os

Operating system  ->    Virtualisation layer 
                        "hypervisor"

physical node           physical node

traditional server      virtual server
```
- virtual machine (VM) are just a file
```
 App  App 
 os   os 
hypervisor
 hardware
```
type 1, known as "bare metal" or "native"
- runs directly on the hardware
- hypervisor runs on the VM
```
         App  App <-|- VM
         os   os  <-|
        hypervisor <- virtual box/ VMware 
 Host ->    OS  windows, linux or mac
        hardware
```
 type 2
- current PC is type two
#### for performance, less layers the better. Type 1 is better
#### Type 2 is easier to use(user friendly)
#### virtualisation is beneficial for scalability
### Main factors
- cost
- scalability
- downtime


### computer diagram:
```
Application
-------
shell
-----
kernel
---
hardware
```
- hardware = pc hardware- kernel = core components
  - interacts with the hardware
- shell = interface between the user and the kernel
    - command line
        - forms of shell
            - sh, bash, dash, tcsl, ksh, zsh
            - sh & bash are used on Ubuntu
            - zsh is used on linux
- main distributions 
  - debian
    - not commerical
    - ubuntu is one
    - kali is based on debian  
  - fedora
    - examples:
      - redhat
      -centos
  - arch linux
    - for advanced users
    - powerful
    - not covered in this course
    