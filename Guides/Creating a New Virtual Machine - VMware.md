## Metadata

2025-02-06 15:10

**Status:** #stage2 

**Tags:** [[Virtualization]]

---
# Creating a new Virtual Machine - VMware

##### Bottom Line Up Front:
- This guide will teach you how to create a new Virtual Machine by using the VmWare Workstation Pro graphical user interface
##### Required Items:
Operating System ISO (disc image of an OS)
 Appropriate amount of disk space and memory

##### Step-By-Step Guide:
- 1. **Open VMware Workstation Pro**
	- Double click on the icon to open the program	![[VMwareWSProIcon.png]]
- 2. **Start the "New Virtual Machine" wizard
	- On the top toolbar, click on "File"
	- Click on "New Virtual Machine"
- 3. **Configure the basic settings using the wizard
	- *Page 1*: Typical
	- *Page 2*: Installer disc image file: Browse to .ISO file and select the file
	- *Page 3*: Enter the username and password credentials you would like to use
	- *Page 4*: Name your virtual machine and choose the storage location for your VM files
	- *Page 5*: Allocate disk space for your VM. I recommend adding +20GB to the recommended size. Leave the "Split virtual disk..." setting as default
	- *Page 6*: Do not customize the hardware yet; I prefer to do this after the OS has finished installing. Click "Finish"
- 4. **Power on the Virtual Machine**
	- 1. Right click on the Virtual Machine you created in steps 2 & 3
	- 2. Hover over the "Power" section of the drop-down menu
	- 3. Click "Start Up Guest"
- 5. **Install the Operating System**
	- ==This step is different depending on which Operating System you are installing==
- 6. **Assign more resources to the VM if necessary**
	- 1. Right click on the VM
	- 2. Click on "Settings..."
	- 3. Click on "Memory" in the left-side pane
		- Adjust the memory settings on the right-side pane
		- Aim for 2x the recommended memory quantity if resources are available
	- 4. Click on "Processors" in the left-side pane
		- Adjust the number of processors and cores per processor
		- Aim for a minimum of 4 processors/1 core per processor
	- 
