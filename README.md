# <h1 align='center'> Operating-System-ISOs
### A collection of operating system iso images for easier access. Anyone can download and dualboot/pure install on their primary machines. 

![tumblr_msu0miicUw1s3wjuno1_500](https://user-images.githubusercontent.com/73013239/108625812-3a783080-7490-11eb-8144-0c243e145d36.gif)

| Operating System | Links |
|----------|---------|
| Ubuntu Linux | https://ubuntu.com/download/desktop/thank-you?version=20.04.2.0&architecture=amd64 |
| Arch Linux | https://archlinux.org/releng/releases/2021.02.01/torrent/ |
| Black Arch Linux | https://ftp.halifax.rwth-aachen.de/blackarch/iso/blackarch-linux-full-2020.12.01-x86_64.iso |
| Kali Linux | https://images.kali.org/kali-linux-2020.4-installer-amd64.iso.torrent |

### **`REMINDERS >`**
#### 1. I did not provide iso distributions for Windows and MAC OS because it is one of the most widely preinstalled operating systems alongside MAC OS. Personally, I am not a big Windows fan either, so...
#### 2. If you are using a Windows PC, be sure to disable "secure boot" in the BIOS settings. Be sure to look up your primary system's key instructions to enter boot menu/ bios environment
#### 3. When you burn your iso to usb disk, you should install [BalenaEtcher](https://www.balena.io/etcher/). This program automatically formats the usb disk to match the input iso. 
#### 4. For Arch Linux, instead of downloading the isos from mirrors in each respective country, I downloaded the torrent file and installed any free torrent file manager to unzip the torrent file. 
#### 5. For Kali Linux and Black Arch Linux, I have booted each into each different usb drives. They are booted on "live persistence"

### **`LIVE USB BOOT PERSISTENCE >`**
#### What is live persistence? - This helps you save files and any configurations of changes of what you did on the system onto your reserved usb drive partition. 
#### So basically, everytime you boot into the operating system, even if you boot it onto a different device, all your credentials will remain saved onto the usb. 
#### How do I reserve a persistence partition? 
##### 1. Download any operating system iso
##### 2. Download [rufus](https://github.com/pbatard/rufus/releases/download/v3.13/rufus-3.13.exe). 
##### 3. Select your iso image at the given prompt when opening rufus, and make sure nothing is in your usb drive as it will be completely reformatted. 
##### 4. When it asks to choose between iso or dd at the prompt, make sure you choose dd (for configurations)
##### 5. Before you run rufus the second time, reserve a space for the partition by dragging an interface. You should reserve half of your usb to boot, and the other remaining half for the persistence partition. 
##### 6. After you run rufus the second time, you should be ready!
#### How do I check if my usb has successfully created a persistence partition? 
##### 1. When you are give boot options when booting into the operating system, be sure to click "persistence"
##### 2. When you enter the desktop window, create any new folder and name it as you like.
##### 3. Reboot into the system again (Again, with live persistence). If your newly created folder does exist at the next boot/login session, then you have created a persistence partition. If your folder is gone, that means the system has not saved your folder or any changes regarding the system, so you have failed. 
