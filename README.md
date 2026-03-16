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

![Screenshot of the GNS3 documentation website showing minimum and recommended requirements for Windows installation.](image)

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

*   Scroll down to "Download the GNS3 all-in-one-installer and click the link

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

> **INFO**
>
> If you want to create complex environments with many devices, your hardware requirements will increase.

## Video

* Video: https://www.youtube.com/watch?v=x9pGYyEqLYs
* Video: https://www.youtube.com/watch?v=IFEDmM_IsxI

### Download the GNS3 all-in-one-installer

Follow these steps to download GNS3 to you MAC. Using a web browser, browse to https://gns3.com and click the **Free Download** link:

![GNS3 Logo](image)

* Select Windows as your operating system to download the GNS3-all-in-one executable file.
* Sign up an account if you do not have one or sign in if you have one already.
* Click download
* Run the installer

![Screenshot of the GNS3 website download page showing a "Thank You!" message and a promotional offer for Engineer's Toolset. A browser download dropdown shows GNS3-2.2.56.1-all-in-one-dach.exe and putty-arm64-0.83-installer.msi as completed downloads.](image)

*   Follow the instruction of the setup wizard

![GNS3 2.2.56.1 Setup Welcome screen showing a "Thank You!" message in the background and the installer window in the foreground.](image)

*   Click next
*   Scroll down to the view the License Agreement
*   Accept the license agreement by clicking "I Agree"

![GNS3 2.2.56.1 Setup License Agreement screen showing the GNU GENERAL PUBLIC LICENSE Version 3.](image)

*   Choose a start menu
*   Leave by defaults

![GNS3 2.2.56.1 Setup window showing "Choose Start Menu Folder" step. The folder "GNS3" is selected in a list of existing folders.](image)

*   Choose components to install
*   Leave it by defaults and click "Next"

![GNS3 2.2.56.1 Setup window showing "Choose Components" step. The installation type is set to "Custom". Components listed include MSVC Runtime 2017 (checked and greyed out), GNS3 Desktop (checked), GNS3 WebClient (unchecked), GNS3 VM (unchecked), and Tools (checked). Space required is 303.9 MB.](image)

Choose install Location

➤ Click next

![GNS3 2.2.56.1 Setup window showing the "Choose Install Location" step. The destination folder is set to C:\Program Files\GNS3. Space required is 303.9 MB and space available is 66.5 GB.](image)

➤ The "License Agreement for Npcap 1.78 Setup" will pop us
* Scroll down
* Click "I Agree"

![Npcap 1.78 Setup - License Agreement window](image)

*   **Installation Option will pop up**
    *   Click "Intall"

![Npcap 1.78 Setup - Installation Options window](image)

*   **Installation is completed**
*   **Click "Next"**

---

### Detailed Window Content Transcription

#### Npcap 1.78 Setup - License Agreement
**License Agreement**
Please review the license terms before installing Npcap 1.78.

Press Page Down to see the rest of the agreement.

> NPCAP COPYRIGHT / END USER LICENSE AGREEMENT
>
> Npcap (https://npcap.com) is a Windows packet sniffing driver and library and is copyright (c) 2013-2023 by Nmap Software LLC ("The Nmap Project"). All rights reserved.
>
> Even though Npcap source code is publicly available for review, it is not open source software and may not be redistributed or used in other software without special permission from the Nmap Project. The standard (free) version is usually limited to installation on five

If you accept the terms of the agreement, click I Agree to continue. You must accept the agreement to install Npcap 1.78.

Nullsoft Install System v3.07
[ I Agree ] [ Cancel ]

---

#### Npcap 1.78 Setup - Installation Options
**Installation Options**
Please review the following options before installing Npcap 1.78

*   [ ] Restrict Npcap driver's access to Administrators only
*   [x] Support raw 802.11 traffic (and monitor mode) for wireless adapters
*   [x] Install Npcap in WinPcap API-compatible Mode

Nullsoft Install System v3.07
[ < Back ] [ Install ] [ Cancel ]

![Screenshot of Npcap 1.78 Setup window showing "Installation Complete. Setup was completed successfully." with a green progress bar at 100% and a "Next >" button highlighted.](image)

➢ Click "Finish"

![Screenshot of Npcap 1.78 Setup window showing "Finished. Thank you for installing Npcap. Npcap has been installed on your computer. Click Finish to close this wizard." with the "Finish" button highlighted.](image)

➢ License Agreement pops up again after installation
* Check the box "I agree to the End User License Agreement and the Privacy Notice" to agree

![Screenshot of the traceNG application showing a License agreement dialog box. The dialog has a checkbox "I agree to the End User License Agreement and the Privacy Notice *" which is checked, and buttons for "Cancel" and "Accept".](image)

➤ Send me tips on how to integrate the new TraceNG with GNS3.. and click "Continue"

![Screenshot of the traceNG application showing a subscription dialog box. The text says "Send me tips on how to integrate the new TraceNG with GNS3 - including updated labs and training." There is a checked checkbox, an email field containing "michaelsalaja@yahoo.com", and a "Continue" button.](image)

➤ License Agreement will pop us again
➤ Click "Accept"

UTM File Edit Virtual Machine View Window Help Sat Jan 31 16:45
Windows 11

![Screenshot of a Windows 11 desktop showing a web browser with the GNS3 download page and an installation window for GNS3 2.2.56.1 in progress.](image)

### GNS3 2.2.56.1 Setup

**Installing**
Please wait while GNS3 2.2.56.1 is being installed.

```description
Progress bar showing installation status.
```

**Execute: C:\Program Files\GNS3\Solar-PuTTY.exe --only-ask**

* Extract: npcap-1.73-oem.exe
* Output folder: C:\Program Files\GNS3\TraceNG
* Running TraceNG
* Execute: C:\Program Files\GNS3\TraceNG\TraceNG.exe 2
* Create shortcut: C:\Users\Public\Desktop\TraceNG.lnk
* Create folder: C:\ProgramData\Microsoft\Windows\Start Menu\Programs\GNS3
* Create shortcut: C:\ProgramData\Microsoft\Windows\Start Menu\Programs\GNS3\Tr...
* Downloading Solar-PuTTY
* Running Solar-PuTTY
* Execute: C:\Program Files\GNS3\Solar-PuTTY.exe --only-ask

GNS3 2.2.56.1 installer
< Back [disabled] | Next > [disabled] | Cancel

---

![Close-up of the GNS3 installation window with a "License Agreement and Privacy Notice" pop-up dialog box.](image)

### License Agreement and Privacy Notice

![Solar-PuTTY Logo](image)

* [ ] I agree to the <u>End User License Agreement</u> and the <u>Privacy Notice</u> <span style="color: red">*</span>

[ Accept ] [ Cancel ]

---

**GNS3 2.2.56.1 Setup**

**Installing**
Please wait while GNS3 2.2.56.1 is being installed.

GNS3 2.2.56.1 installer
< Back [disabled] | Next > [disabled] | Cancel

-4°C Stark bewölkt | Search | Windows Taskbar icons

![Screenshot of GNS3 2.2.56.1 Setup showing a License Agreement and Privacy Notice pop-up window. The pop-up has a checkbox "I agree to the End User License Agreement and the Privacy Notice *" which is checked, and an error message "Please accept the End User License Agreement and Privacy Notice to proceed". There are "Accept" and "Cancel" buttons at the bottom.](image)

Ø SolarPuTTy tips will pop up
* Type in your email and click "Continue"

![Screenshot of GNS3 2.2.56.1 Setup with a Solar-PuTTY pop-up window. The pop-up asks to "Send me tips on how to integrate the new Solar-PuTTY with GNS3 - including updated labs and training." A checkbox is checked and the email field contains "michaelsalaja@yahoo.com". There is a "Continue" button. The main installer window in the background shows "Next" button is active.](image)

Ø Installation completed
* Click "Next"

![GNS3 2.2.56.1 Setup window showing installation complete with a log of actions including downloading Solar-PuTTY and creating shortcuts.](image)

Ø Solarwinds Engineer’s Toolset will pop up
* Click Yes and “Next” If you want to

![GNS3 2.2.56.1 Setup window for Solarwinds Engineer's Toolset offering a 14-day trial of 60 network tools with Yes and No radio buttons.](image)

All installations are complete.

![GNS3 2.2.56.1 Setup window showing the completion screen with a "Start GNS3" checkbox selected and a "Finish" button.](image)

### Setting Up GNS3

*   **Launch GNS3:** Open the GNS3 application.

*   **Setup Wizard:** The first time it opens, the Setup Wizard will appear.
*   <mark>*Choose to run appliances on the local machine (local server). And click "Next"*</mark>

![GNS3 application interface showing the Setup Wizard dialog box with the "Run appliances on my local computer" option selected.](image)

![GNS3 Setup Wizard - Local server configuration](image)

![GNS3 Setup Wizard - Local server status](image)

Ø Configure Components: Ensure the Npcap/WinPcap driver is installed for network connectivity.

*   Verification: Ensure the server summary in the bottom-left corner turns green, indicating the local server is running.
*   Click "Finish"

![Screenshot of GNS3 Setup Wizard summary window showing Server type: Local, Path: C:\Program Files\GNS3\gns3server.EXE, Host: localhost, and Port: 3080. The Finish button is highlighted.](image)

### <p align="center"><font color="#D97E41">Configuring GNS3</font></p>

*   Create a project
*   Click ok

![Screenshot of the GNS3 main interface showing the Project Library, End devices panel with Cloud, NAT, and VPCS options, and the Servers Summary indicating the local server is running.](image)

* Click on the arrow box
* Navigate to "NAT" to drag switch 1 into the topology

![Screenshot of a network simulation software interface showing the 'Filter' menu with options for Cloud, NAT, and VPCS. A mouse cursor is hovering over the 'Browse End Devices' icon (represented by two arrows pointing in opposite directions).](image)

* Click on the computer boy
* Navigate to "VPCS" to drag two computers into the topology

![Screenshot of the network simulation software interface with the 'Browse End Devices' icon selected. The 'Filter' menu shows Cloud, NAT, and VPCS. A mouse cursor is hovering over the 'End Devices' icon (represented by a computer monitor).](image)

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

![Screenshot of GNS3 interface showing a network topology with two VPCS (PC1 and PC2) connected to a Switch1. The nodes are currently stopped (indicated by red squares in the Topology Summary).](image)

![Screenshot of GNS3 interface showing the same network topology. The user is about to click the green 'Start' button in the toolbar.](image)

*   Click the Green Icon up in the middle pane to start the devices
*   Then they will turn green
*   Output of the successful connection established between both VPCS

![Screenshot of GNS3 interface showing the network topology with all nodes started. The status indicators in the Topology Summary are now green circles.](image)

*   Now we can assign IP addresses to the
*   To do this, go to the console on VPCS – PC1 or click on the "Greater than hyphen" icon on the upper pane to start both consoles

![Toolbar in GNS3 showing the "Greater than hyphen" icon selected by a cursor](image)

*   This will lead to a terminal

![GNS3 interface showing the terminal console for PC1 open with the Solar-PuTTY tool](image)

*   Assign IP address to PC1
    *   Type `ip 10.1.1.1 255.255.255.0`

![Terminal window showing the command and output for assigning an IP address](image)

```
PC1> ip 10.1.1.1 255.255.255.0
Checking for duplicate address...
PC1 : 10.1.1.1 255.255.255.0
```

*   Type "show ip" and press enter
*   Ip is successfully assigned

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

![Screenshot of a terminal window showing the 'show ip' command output followed by the 'save' command. The 'save' command and its output are highlighted with a red rectangle.](image)

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

*   Type command "Save" and press enter

![Screenshot of a terminal window showing the 'save' command being executed.](image)

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

Ø Ping 10.1.1.1 from 10.1.1.2 to establish if packets are being dropped between 10.1.1.2 and 10.1.1.1

![Screenshot of a terminal window showing the IP configuration and a successful ping test.](image)

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

![Terminal window showing ping results from PC1 to 10.1.1.2](image)

$\text{\textgreater}$ To change the settings on the appearance
*   Got to settings at the right pane
*   Click "General"
*   Click "Launch PuTTY"
*   Click "Change"
*   Change the size or font or font style

![Solar-PuTTY settings interface with PuTTY Configuration font dialog open](image)

**General**

**KEYBOARD SHORTCUTS**
[ ] Disable keyboard shortcuts

**PuTTY Configuration**
*   **Category:**
    *   Session
        *   Logging
    *   Terminal
        *   Keyboard
        *   Bell
    *   **Font**
*   **Configure the appearance of PuTTY's window**
*   **Adjust the use of the cursor**
    *   **Cursor appearance:**
        *   (•) Block
        *   ( ) Underline
        *   ( ) Vertical line
*   **Font:**
    *   **Font:** Consolas [selected]
    *   **Font style:** Regular [selected]
    *   **Size:** 20 [selected]
*   **Sample:** AaBbYyZz
*   **Script:** Western

[OK] [Cancel]

solarwinds | Solar-PuTTY free to                                                                        SolarWinds Worldwide, LLC. All rights reserved.

* Click “Session”
* Click “Default
* Click “Save”
* Click “Cancel” to exit

<br/>

<h3 style="color: #E07A5F; text-align: center">Conclusion</h3>

This lab project provides you with a straightforward and practical understanding of how to install and configure GSN3 to be able to create a network topology. The configuration helps enhance efficiency and scalability of my network infrastructure. Before the installation took place, I installed PuTTY on my Windows 11 VM on UTM to have both software work together. For example, prerequisite for configuring port security on an access port is the combination of GSN3 and PuTTY SSH Client. In my next project, I intend to focus on configuring port security on an access port with GSN3 and PuTTy SSH Client.
