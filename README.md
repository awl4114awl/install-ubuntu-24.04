<p align="center">
<img src="https://i.imgur.com/b7V2FPv.png" height="40%" width="40%" alt="install kali"/>
</p><h1>How to Install Ubuntu 24.04 on Windows 10/11 using Oracle VirtualBox</h1>

In this tutorial, I will show you how to download and install Ubuntu 24.04 on VirtualBox in Windows 10/11, step by step. Whether you're a beginner or an experienced user, this guide will help you set up Ubuntu on a virtual machine, allowing you to run a full Ubuntu environment without affecting your main operating system. Let's get right into it!

First, we'll go over the process of downloading the necessary software: Oracle VirtualBox and the Ubuntu 24.04 ISO file. Oracle VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product that is free and open-source. It allows you to create and manage virtual machines on your computer. The Ubuntu ISO file is the disk image that contains the operating system we will be installing.

Once we've downloaded the software, we'll proceed with creating a new virtual machine in VirtualBox. This involves setting up the virtual hardware (such as memory, storage, and network settings) to ensure that our virtual machine runs smoothly. We'll allocate enough memory and storage to the VM, configure the virtual disk, and set up additional settings to optimize performance.

After configuring the virtual machine, we'll move on to the installation of Ubuntu 24.04. This process includes booting from the ISO file, following the installation prompts, and configuring the system settings such as language, time zone, and user account. We will cover each step in detail to ensure you have a seamless installation experience.

Finally, we will go through the post-installation steps to enhance your Ubuntu experience, such as installing VirtualBox Guest Additions for better integration and performance. This includes enabling features like shared clipboard, drag and drop, and 3D acceleration, making it easier to use Ubuntu alongside your main OS.

By the end of this tutorial, you will have a fully functional Ubuntu 24.04 virtual machine running on your Windows 10/11 system. Let's get started!

<h2>Languages and Utilities Used</h2>

    - Oracle VirtualBox: For creating and running the virtual machine.
    - Ubuntu 24.04 ISO file: The installation image for Ubuntu.
    - Terminal: For verifying the installation.

<h2>Environments Used</h2>

    - Ubuntu 24.04 VM
    - Windows 10 (22H2) or Windows 11

<h2>Program Walk-through:</h2>

    Download Ubuntu 24.04:
<p align="center">
<img src="https://i.imgur.com/F6t5Th6.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Launch VirtualBox and select "New". Create the name, and select the operating system:
<p align="center">
<img src="https://i.imgur.com/l5MvRTg.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Next, modify hardware settings: 
<p align="center">
<img src="https://i.imgur.com/RXSgjvO.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Allocate the storage space to 30 GB or higher: <br/>
<p align="center">
<img src="https://i.imgur.com/enzyuTe.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Review summary, select "Finish": 
<p align="center">
<img src="https://i.imgur.com/k98ZJ1h.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    After creating VM, navigate to Settings --> General --> Advanced and change 'Shared Clipboard' to Bidirectional. I like to change 'Drag'n'Drop' to Bidirectional too.:
<p align="center">
<img src="https://i.imgur.com/39b8kYV.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Now head to the sidebar and select 'Display' and select '☑ Enable 3D Acceleration': 
<p align="center">
<img src="https://i.imgur.com/YDEOc1L.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    We will then go to 'Storage'. Under the IDE controller, click on "Empty", click the DVD icon, and select 'Choose a disk file...': 
<p align="center">
<img src="https://i.imgur.com/0MuOvKC.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Import the Ubuntu ISO:
<p align="center">
<img src="https://i.imgur.com/aJz7bYY.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Once that's done, you're good to select "Start":
<p align="center">
<img src="https://i.imgur.com/LHkT0Jq.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    You will be met with the GNU GRUB installer window. Choose "Try or Install Ubuntu":
<p align="center">
<img src="https://i.imgur.com/d7fqaVN.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Choose your language, skip the accessibility settings that show up next, also skip keyboard settings:
<p align="center">
<img src="https://i.imgur.com/4YnHg5V.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Select "Install Ubuntu":
<p align="center">
<img src="https://i.imgur.com/PyoVpU1.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Select interactive installation:
<p align="center">
<img src="https://i.imgur.com/JmQtUGM.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    We have the option to install Ubuntu with either the default selection of apps or we can choose extended for more options. We will do extended.:
<p align="center">
<img src="https://i.imgur.com/P7vO83n.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Next, select both options to optimize your computer by installing recommended drivers: 
<p align="center">
<img src="https://i.imgur.com/hslt8Sq.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    For the installation type, choose "Erase disk" and click on "Next": 
<p align="center">
<img src="https://i.imgur.com/zFdZXr8.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Now create a user account: 
<p align="center">
<img src="https://i.imgur.com/DHfUUqb.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Select your time zone:
<p align="center">
<img src="https://i.imgur.com/3aYpWVA.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Review the summary of your installation, and select "Install" when done.:
<p align="center">
<img src="https://i.imgur.com/9ZOGaYe.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    This will take a minute. Sit back, and please be patient:
<p align="center">
<img src="https://i.imgur.com/09VU4uL.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    Once it is finished installing, you will be met with the option to continue testing or to restart now. Go ahead and click "Restart Now": 
<p align="center">
<img src="https://i.imgur.com/4mMHCef.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    You have successfully installed Ubuntu 24.04:
<p align="center">
<img src="https://i.imgur.com/tp53jxu.jpeg" height="80%" width="80%" alt="install ubuntu"/>
<br />
<br />
    
    And that's pretty much it. Thanks for reading my tutorial on installing Ubuntu 24.04.

