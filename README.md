# Graphical Network Simulator-3 (GNS3)

## Introduction

This project aims to help the community understand how to download, install, and configure Graphical Network Simulator-3 (GNS3) on Windows 11 virtual machine on a UTM M1/M2/M3 11 in 2025. The configuration entails guidance for creating a topology. Topology refers to the arrangement or configuration of the virtual network connections within the virtual machine (VM) environment. It defines how the virtual network interfaces and components are interconnected and organized

## Download and Installation

This download is for Windows 11 on UTM

*   Open a Web browser
*   Google "Graphical Network Simulator-3 (GNS3)"
*   Enter the PuTTy Official Website
*   Download
    -   Navigate to the official GNS3 Windows Install
*   Check the minimum requirements

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/36bcde437ff45b0be00cc9eb22a196bc806fb427/Figure%201.png)
Figure 1

<table>
  <thead>
    <tr>
        <th>Item</th>
        <th>Requirement</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>Operating System</td>
        <td>Windows 7 (64 bit) or later</td>
    </tr>
    <tr>
        <td>Processor</td>
        <td>2 or more Logical cores</td>
    </tr>
    <tr>
        <td>Virtualization</td>
        <td>Virtualization extensions required. You may need to enable this via your computer's BIOS.</td>
    </tr>
    <tr>
        <td>Memory</td>
        <td>4 GB RAM</td>
    </tr>
    <tr>
        <td>Storage</td>
        <td>1 GB available space (Windows Installation is &lt; 200 MB).</td>
    </tr>
    <tr>
        <td>Additional Notes</td>
        <td>You may need additional storage for your operating system and device images.</td>
    </tr>
  </tbody>
</table>

> **INFO**
> The hardware requirements listed here are minimum requirements for a small GNS3 environment. If you want to create complex environments with many devices, your hardware requirements will increase.

## Recommended Requirements
The following are the recommended requirements for a Windows GNS3 environment:

<table>
  <thead>
    <tr>
        <th>Item</th>
        <th>Requirement</th>
    </tr>
  </thead>
</table>


* Mac
* Linux
* ESXi
* Remote Server
* Download the GNS3 VM
* Download for Windows 32-bit
* One GNS3 server, multiple clients
* Upgrade GNS3
* GNS3 on Equinix
* Setup wizard for local server
* Setup wizard for GNS3 VM
* Your first GNS3 topology
* Your first Cisco topology
* Using GNS3
* Emulators


*   Scroll down to "Download the GNS3 all-in-one-installer and click the link

### Download the GNS3 all-in-one-installer

Follow these steps to download GNS3 to you MAC. Using a web browser, browse to https://gns3.com and click the **Free Download** link:

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/36bcde437ff45b0be00cc9eb22a196bc806fb427/Figure%202.png)
Figure 2


* Select Windows as your operating system to download the GNS3-all-in-one executable file.
* Sign up an account if you do not have one or sign in if you have one already.
* Click download
* Run the installer

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/36bcde437ff45b0be00cc9eb22a196bc806fb427/Figure%203.png)
Figure 3


*   Follow the instruction of the setup wizard

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/36bcde437ff45b0be00cc9eb22a196bc806fb427/Figure%204.png)
Figure 4


*   Click next
*   Scroll down to the view the License Agreement
*   Accept the license agreement by clicking "I Agree"

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/36bcde437ff45b0be00cc9eb22a196bc806fb427/Figure%205.png)
Figure 5

*   Choose a start menu
*   Leave by defaults

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/36bcde437ff45b0be00cc9eb22a196bc806fb427/Figure%206.png)
Figure 6


*   Choose components to install
*   Leave it by defaults and click "Next"

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/36bcde437ff45b0be00cc9eb22a196bc806fb427/Figure%207.png)
Figure 7


Choose installation Location

➤ Click next

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%208-1.png)
Figure 8

➤ The "License Agreement for Npcap 1.78 Setup" will pop us
* Scroll down
* Click "I Agree"

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%208.png)
Figure 9


*   **Installation Option will pop up**
    *   Click "Install"

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%209.png)
Figure 10

*   **Installation is completed**
*   **Click "Next"**

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2010.png)
Figure 11


➢ Click "Finish"

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2011.png)
Figure 12

➢ License Agreement pops up again after installation
* Check the box "I agree to the End User License Agreement and the Privacy Notice" to agree

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2012.png)
Figure 13


➤ Send me tips on how to integrate the new TraceNG with GNS3.. and click "Continue"

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2013.png)
Figure 14

➤ License Agreement will pop us again
➤ Click "Accept"

UTM File Edit Virtual Machine View Window Help Sat Jan 31 16:45
Windows 11

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2014.png)
Figure 15

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2015.png)
Figure 16

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2016.png)
Figure 17

Ø SolarPuTTy tips will pop up
* Type in your email and click "Continue"

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2017.png)
Figure 18

Ø Installation completed
* Click "Next"

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2018.png)
Figure 19

Ø Solarwinds Engineer’s Toolset will pop up
* Click Yes and “Next” If you want to

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2019.png)
Figure 20

All installations are complete.

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2020.png)
Figure 21

### Setting Up GNS3

*   **Launch GNS3:** Open the GNS3 application.

*   **Setup Wizard:** The first time it opens, the Setup Wizard will appear.
*   <mark>*Choose to run appliances on the local machine (local server). And click "Next"*</mark>

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2021.png)
Figure 22

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2022.png)
Figure 23

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2023.png)
Figure 24

Ø Configure Components: Ensure the Npcap/WinPcap driver is installed for network connectivity.

*   Verification: Ensure the server summary in the bottom-left corner turns green, indicating the local server is running.
*   Click "Finish"

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2024.png)
Figure 25

### <p align="center"><font color="#D97E41">Configuring GNS3</font></p>

*   Create a project
*   Click ok

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2025.png)
Figure 26

* Click on the arrow box
* Navigate to "NAT" to drag switch 1 into the topology

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2026.png)
Figure 27

* Click on the computer boy
* Navigate to "VPCS" to drag two computers into the topology

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2027.png)
Figure 28

* Click on "add a link"
* Click on PC1
* Click Ethernet0
* Then drag the file to Switch 1
* Click on switch 1
* Click Ethernet 0
* Click on Switch 1
* Click Ethernet 1
* Drag the file to PC2
* Click PC2
* Click Ethernet 1

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2028.png)
Figure 29

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2029.png)
Figure 30

*   Click the Green Icon up in the middle pane to start the devices
*   Then they will turn green
*   Output of the successful connection established between both VPCS

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2030.png)
Figure 31

*   Now we can assign IP addresses to the
*   To do this, go to the console on VPCS – PC1 or click on the "Greater than hyphen" icon on the upper pane to start both consoles

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2031.png)
Figure 32

*   This will lead to a terminal

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2032.png)
Figure 32

*   Assign IP address to PC1
    *   Type `ip 10.1.1.1 255.255.255.0`

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2033.png)
Figure 33

```
PC1> ip 10.1.1.1 255.255.255.0
Checking for duplicate address...
PC1 : 10.1.1.1 255.255.255.0
```

*   Type "show ip" and press enter
*   Ip is successfully assigned

  ![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2034.png)
  Figure 34

```
PC1> show ip

NAME            : PC1[1]
IP/MASK         : 10.1.1.1/24
GATEWAY         : 255.255.255.0
DNS             :
MAC             : 00:50:79:66:68:00
LPORT           : 10006
RHOST:PORT      : 127.0.0.1:10007
MTU:            : 1500

PC1> █
```

*   Type command "Save" and press enter

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2035.png)
Figure 35


```
PC1> show ip

NAME            : PC1[1]
IP/MASK         : 10.1.1.1/24
GATEWAY         : 255.255.255.0
DNS             :
MAC             : 00:50:79:66:68:00
LPORT           : 10006
RHOST:PORT      : 127.0.0.1:10007
MTU:            : 1500

PC1> save
Saving startup configuration to startup.vpc
.  done

PC1> █
```

*   Navigate to PC2
*   Assign IP address to PC2
*   Type ip 10.1.1.2 255.255.255.0

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2036.png)
Figure 36


```
PC2> ip 10.1.1.2 255.255.255.0
Checking for duplicate address...
PC1 : 10.1.1.2 255.255.255.0
```

*   Show ip

*   ip is successfully assigned

```
PC2> show ip

NAME            : PC2[1]
IP/MASK         : 10.1.1.2/24
GATEWAY         : 255.255.255.0
DNS             :
MAC             : 00:50:79:66:68:01
LPORT           : 10004
RHOST:PORT      : 127.0.0.1:10005
MTU:            : 1500

PC2> █
```

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2037.png)
Figure 37

*   Type command "Save" and press enter
  

```
PC2> show ip

NAME            : PC2[1]
IP/MASK         : 10.1.1.2/24
GATEWAY         : 255.255.255.0
DNS             :
MAC             : 00:50:79:66:68:01
LPORT           : 10004
RHOST:PORT      : 127.0.0.1:10005
MTU:            : 1500

PC2> save
Saving startup configuration to startup.vpc
. done

PC2> █
```
![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2038.png)
Figure 38


Ø Ping 10.1.1.1 from 10.1.1.2 to establish if packets are being dropped between 10.1.1.2 and 10.1.1.1

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2039.png)
Figure 39

```
PC2> ip 10.1.1.2 255.255.255.0
Checking for duplicate address...
PC1 : 10.1.1.2 255.255.255.0

PC2> ping 10.1.1.1
84 bytes from 10.1.1.1 icmp_seq=1 ttl=64 time=5.029 ms
84 bytes from 10.1.1.1 icmp_seq=2 ttl=64 time=23.007 ms
84 bytes from 10.1.1.1 icmp_seq=3 ttl=64 time=2.278 ms
84 bytes from 10.1.1.1 icmp_seq=4 ttl=64 time=21.380 ms
84 bytes from 10.1.1.1 icmp_seq=5 ttl=64 time=3.388 ms
```

$\text{\textgreater}$ Ping 10.1.1.2 from 10.1.1.1 to establish if packets are being dropped between 10.1.1.1 and 10.1.1.2

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2040.png)
Figure 40

$\text{\textgreater}$ To change the settings on the appearance
*   Got to settings at the right pane
*   Click "General"
*   Click "Launch PuTTY"
*   Click "Change"
*   Change the size or font or font style

![image alt](https://github.com/Michaelsalaja/Network-Engineering-Lab/blob/40e1775a5956d7cdc515a5020acb05af7cbf75de/Figure%2041.png)
Figure 41

*   Click "Session"
*   Click "Default"
*   Click "Save"
*   Click "Cancel" to exit

## Conclusion

This lab project provides you with a straightforward and practical understanding of how to install and configure GSN3 to be able to create a network topology. The configuration helps enhance efficiency and scalability of my network infrastructure. Before the installation took place, I installed PuTTY on my Windows 11 VM on UTM to have both software work together. For example, prerequisite for configuring port security on an access port is the combination of GSN3 and PuTTY SSH Client. In my next project, I intend to focus on configuring port security on an access port with GSN3 and PuTTy SSH Client.
