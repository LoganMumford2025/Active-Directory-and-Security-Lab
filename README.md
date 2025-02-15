# Active-Directory-and-Security-Lab

## Objective
As I transition into IT, gaining hands-on experience with Active Directory can be challenging without direct access to enterprise environments. This lab is designed to bridge that gap by allowing me to install and configure Windows Server 2022 with Active Directory, set up a Windows 10 end-user machine, and create a domain to manage users and groups. Additionally, I will incorporate a Kali Linux VM for simulated attacks and a Splunk VM for monitoring, enabling me to analyze security threats in a controlled environment. This lab will serve as a foundational sandbox to refine my skills, troubleshoot real-world scenarios, and deepen my understanding of IT and cybersecurity as I progress in my career.

### Skills Learned

- Installing and configuring Splunk Virtual Machine
- Installing and configuring Windows Server 2022
- Creating OU in Active Directory and managing users
- Enhanced knowledge of cybersecurity threats
- Learn password reset and privealages for different user groups

### Tools Used

- Splunk SIEM to monitor endpoint and Windows Server 2022
- Sysmon for generating endpoint logs and getting experience reading them

### Steps

#### Download VM .iso files for lab
<ul>
  <li>Download .iso files for Windows 10 Pro (https://www.microsoft.com/en-us/software-download/windows10)</li>
    <ul>
      <li>Click Download under Create Windows 10 Installation Media</li>
      <li>Click executable file in downloads to start the media creation wizard</li>
      <li>When prompted "What to Do" click create installation media and click next twice</li>
      <li>Under "Choose Which Media to Use" choose "ISO File" and hit next</li>
      <li>Pick a folder to save your .iso file to</li>
    </ul>
  <li>Download .iso files for Windows Server 2022 (https://info.microsoft.com/ww-landing-windows-server-2022.html)</li>
    <ul>
      <li>Fill in the registration form and click "Download Now"</li>
      <li> Click the hyperlink for 64-Bit edition to begin the download</li>
      <li> Once downloaded, be sure to move .iso file into the same folder as the Windows 10 folder for easy management</li>
    </ul>
  <li>Download .iso files for Kali Linux (https://www.kali.org/get-kali/#kali-installer-images)</li>
    <ul>
        <li>Scroll down and look for Kali Linux net installer (note: your VM will need internet access during initial setup of Kali Linux)</li>
        <li>After download is complete, be sure to move this file to the same folder with the Windows 10 and Windows Server 2022 .iso files</li>
    </ul>
  <li>Download .iso files for Ubuntu 24.04.1 LTS (https://ubuntu.com/download/server)</li>
  <li>Click Download and once downloaded, move .iso file to project folder with other .iso files</li>
</ul>

### Creating Virtual Machines in Proxmox and Installing Operating Systems

<ul>
  
</ul>

-Ubuntu 24.04 Live Server LTS

*Ref 1: Network Diagram* ![Home Directory Edited](https://github.com/user-attachments/assets/33f4c092-a723-4d78-9cf4-de14d0d9d3bd)
