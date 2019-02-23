# HackCU 2019: Vehicle Hacking Workshop
This is the repository for the Neutral Vehicle Project's car hacking workshop. This README contains installation instructions for downloading the tools needed to participate in the workshop, as well as instructions for following along with the demo.

## Workshop layout
The workshop is split into two pieces:

1. Network sniffing with Wireshark
2. Vehicle hacking and reverse engineering with `can-utils`

## Required tools
The following tools are required for this workshop:

1. [Wireshark](https://www.wireshark.org/)
2. [can-utils](https://github.com/linux-can/can-utils)
3. [ICSim](https://github.com/zombieCraig/ICSim)

We highly recommend that you use our virtual machine image instead of trying to set up these tools yourself. The main exception is if you already have an Ubuntu-based virtual machine (include the Computer Science Department's VM), in which case installation shouldn't be too difficult.

### Installation
#### Installing on Ubuntu-based Linux distros
If you have a virtual machine that is running an Ubuntu-based distribution (including Xubuntu, MATE, etc.), you can use the following commands to install Wireshark, can-utils, and ICSim.

**NOTE**: if you have the [CU Boulder Computer Science Department VM](https://foundation.cs.colorado.edu/vm/), *you can install everything with the instructions below*! This is because the CS Dept.'s VM is based on Xubuntu. 

```bash
sudo apt install git wireshark libsdl2-dev libsdl2-image-dev can-utils
git clone https://github.com/zombieCraig/ICSim.git
```

#### Installing individual tools
If you *do* wish to install the tools above by yourself, here is how you can do so:

* **Wireshark**: Wireshark can be installed on multiple operating systems. Visit https://www.wireshark.org/ to find instructions to download Wireshark and run it on your computer.
* **can-utils and ICSim**: if you have a Unix-based system, these may work on your computer. You will have to clone both of these from their respective repositories:
  * can-utils: https://github.com/linux-can/can-utils
  * ICSim: https://github.com/zombieCraig/ICSim
