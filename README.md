## Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
## NAME: Viswapriya S
## REG NO: 212225230311
## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.
## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
   *Machine with Internet access
   *Minimum 4 GB RAM
   *Sufficient storage space
## Steps:
## 1.Download Oracle VM VirtualBox:
    *Visit Oracle VirtualBox Official Site
    *Download installer for your OS (Windows/macOS/Linux).
## 2.Install Oracle VM VirtualBox (Example: Windows):
    *Launch Installer → Allow Changes → Click Next.
    *Choose Installation Options → Click Next.
    *Accept Network Interface Warning → Click Yes.
    *Click Install.
    *Finish Installation and Launch VirtualBox.
## 3.Configure VirtualBox:
    *Open VirtualBox.
    *Click New → Name VM → Select Type (Linux/Windows) and Version.
## Allocate:
   *Minimum 2 GB RAM
   *Create Virtual Hard Disk (20 GB recommended).
   *Start Virtual Machine and provide ISO to install OS.
## Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
   *Oracle VM VirtualBox Installed
   *4 GB RAM and 20 GB Storage Minimum
   *Kali Linux ISO image
## Steps:
## 1.Download Kali Linux ISO:
  *Visit Kali Linux Official Site
  *Download 64-bit ISO (Installer version).
  *Create a New Virtual Machine:
  *Open VirtualBox → Click New.
  *Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
## Allocate Memory:
  *Minimum 2 GB RAM (recommended 4 GB).
  *Create Virtual Hard Disk:
  *Select VDI (VirtualBox Disk Image).
  *Choose Dynamically allocated.
  *Set Disk size to 20 GB or more.
## Configure ISO Image:
  *Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
## Start Installation:
  *Boot Virtual Machine → Choose Graphical Install.
  *Set Language, Region, Keyboard.
  *Configure Network → Set Hostname (e.g., kali).
  *Set root password.
  *Disk Partitioning: Use entire disk → All files in one partition.
  *Install System → Install GRUB Bootloader → Finish Installation.
## Login to Kali Linux:
  *Use root credentials.
  *(Optional) Install Guest Additions:
  *Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
## Snapshots:
AWS Account Creation Snapshot

## Snapshot 1: Installing Oracle VirtualBox image

## Snapshot 2: Kali Running in Virtual image

## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
  *Open-source operating system.
  *Kernel manages communication between hardware and software.
  *Commands are case-sensitive.
## Linux Commands:
## 1.ls Command:
The ls command is used to display a list of content of a directory.
## Syntax:
    ls

<img width="714" height="70" alt="image" src="https://github.com/user-attachments/assets/ebad07a2-c1d4-4672-9395-f4f6ed8ac5ed" />

## 2.pwd Command:
The pwd command is used to display the location of the current working directory.
## Syntax:
    pwd

<img width="193" height="67" alt="image" src="https://github.com/user-attachments/assets/344b1c5e-1338-4dfc-ab34-f3a72faf95a2" />

## 3.mkdir Command:
The mkdir command is used to create a new directory under any directory.

## Syntax:
    mkdir <directory_name> 

<img width="364" height="49" alt="image" src="https://github.com/user-attachments/assets/b8607e18-034e-4703-9fda-4bc851ba0405" />

## 4.rmdir Command:
The rmdir command is used to delete a directory.
## Syntax:
    rmdir <directory_name>

<img width="308" height="50" alt="image" src="https://github.com/user-attachments/assets/2ba80332-7b4f-4b3c-a4a1-f50b5b4c4303" />


## 5.cd Command :
The cd command is used to change the current directory
## Syntax:
    cd <directory_name>

<img width="223" height="42" alt="image" src="https://github.com/user-attachments/assets/3939f703-1e2a-4bf7-8241-01e282c0ba2e" />

## 6.cat Command:
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.
## Syntax:
    cat [options] [file_name]

<img width="632" height="73" alt="image" src="https://github.com/user-attachments/assets/d75c89bd-b4c5-4716-a370-3d325ac9f9e1" />
<img width="866" height="71" alt="image" src="https://github.com/user-attachments/assets/b28ee00d-499e-4df1-b109-98bb1cb4e60f" />

## 7.cp Command:
The cp command is used to copy a file or directory.
## Syntax:
    cp [source] [destination]

<img width="300" height="52" alt="image" src="https://github.com/user-attachments/assets/56a2eff4-100d-4b39-a745-8f3e98dc7f14" />
<img width="831" height="62" alt="image" src="https://github.com/user-attachments/assets/06a974ba-7c19-41ff-8a3b-319830d22c07" />

## 8.mv Command:
The mv command is used to move a file or a directory form one location to another location.
## Syntax:
    mv [source] [destination]

<img width="293" height="52" alt="image" src="https://github.com/user-attachments/assets/097e7713-4d7a-44ef-aad7-70ca867ec28c" />
<img width="339" height="64" alt="image" src="https://github.com/user-attachments/assets/3fb930b3-9eec-4ebc-b293-041920c12e98" />

## 9.touch Command:
Create empty file.
## Syntax:
    touch [filename]

<img width="185" height="44" alt="image" src="https://github.com/user-attachments/assets/efb240f0-272c-4770-b924-7691ca033e71" />

## 10.vi Command:
Edit file contents using editor.
## Syntax:
    vi [filename]

<img width="192" height="51" alt="image" src="https://github.com/user-attachments/assets/759dcba3-33d9-42fc-b391-5bb4412f6a20" />

## Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.

