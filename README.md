## Description

This repository provides a patch for VMware Workstation host modules (`vmmon` and `vmnet`)
Automated installation (replaces vmmon/vmnet and runs vmware installation script to update with the new modules)
Workstation versions 17.5.2 and 17.6
## Tested on

- Linux: VMware Workstation Pro: Version 17.5.2, 17.6
- Linux Kernels: Up to version 6.10.x - 6.11.x
- Distributions: Debian-based, Arch-based Fedora

## Installation
```bash

git clone https://github.com/x6h057/vm-host-modules-17.6.git 
cd vm-host-modules-17.6

make
sudo make install
```
