# SDN-based-Cloud-center-using-Mininet

Simulation of SDN based Cloud center using Mininet, Authors - Bhushan Hiwase

Submitted for class project, Subject; Broadband Communication Networks, SJSU Instructed by Prof Nadir Mir.

Following are the steps for installation:

1. Install Hypervisor (I have used VmWare Workstation15)
2. Install Mininet in the device (install mininet using 'sudo apt-get install mininet' command)
3. Install SDN controller. I have used RYU controller for this project (use command "%pip install ryu")
4. Install a virtual switch OpenvSwitch (use commands “sudo apt-get install qemu-kvm libvirt-bin ubuntu-vm-builder bridge-utils” & “sudo apt-get install openvswitch-switch)

After Installation is complete, Save and run the python files (Topology1, Topology2, Topology3), while the RYU controller is running in the background.
To run the python files use command "python filename.py" and to run the controller, use command "./bin/ryu-manager --verbose ryu/app.simple_switch_13.py" in the RYU directory.
 
