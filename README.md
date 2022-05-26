# **JameOS** #

## **Table Of Contents** ##

- [What is JameOS](#what-is-jameos)
- [Why use JameOS](#why-use-jameos)
- [Versions](#versions)
- [JameOS 1.0](#jameos-10)
- [JameOS 1.1](#jameos-11)
- [Which Version Should I use](#which-version-should-i-use)
- [Download Link](#download-link)
- [How To Install](#how-to-install)
- [Post Install Advice](#post-install-advice)
- [Where To Find Help](#where-to-find-help)
- [Upcoming Features](#upcoming-features)
- [How To Support Me](#how-to-support-me)

## What Is JameOS ##

JameOS is a school project I created for the IB personal project.

## Why Use JameOS ##

JameOS is a lightweight Linux distro that aims to be easy to use for people wanting to try linux.

## Versions ##

There are currently 2 versions of JameOS: [1.0](#jameos-10 "Go to JameOS 1.0") and [1.1](#jameos-11 "Go to JameOS 1.1").

## JameOS 1.0 ##

JameOS 1.0 is based on [Linux From Scratch](https://www.linuxfromscratch.org/ "Linux From Scratch").

**Some features of JameOS 1.0:**

JameOS 1.0 is command line only, and as such is super lightweight but most likely won't meet your everyday needs.

**Why use JameOS 1.0?**

- Really, I have no idea.

**Disadvantages of JameOS 1.0?**

- Command line only.
- No package manager. 

**NOTE:** JameOS 1.0 has been discontinued and is currently not avalible in downloads.

## JameOS 1.1 ##

JameOS 1.1 is based off of Arch Linux.

**Some features of JameOS 1.1:**

- JameOS 1.1 can boot on systems using [secure boot](https://docs.microsoft.com/en-us/windows-hardware/design/device-experiences/oem-secure-boot "Microsoft Docs") and is set up to be easily used in a [dual boot](https://en.wikipedia.org/w/index.php?title=Multi-booting "Wikipedia") configuration. 
- JameOS 1.1 has a fully functional [KDE Plasma](https://kde.org/plasma-desktop/ "KDE") desktop and should be functional for most everyday use.
- JameOS 1.1 has the ability to run some windows applications using a program called [Wine](https://www.winehq.org/ "WineHQ").
- JameOS 1.1 has the ability to mount microsoft filesystems such as [NTFS](https://docs.microsoft.com/en-us/windows-server/storage/file-server/ntfs-overview "Microsoft Docs") and [FAT32](https://en.wikipedia.org/wiki/File_Allocation_Table "Wikipedia").
- JameOS 1.1 has a graphical app installer preinstalled in order to make installing apps much similar.

**Why use JameOS 1.1?**

- If you like the power and control of Arch Linux but the simplicity and ease of use of Manjaro.
- Staying up to date most of the time on the newest software when it is realized.
- If you want an operating system that boots straight from a usb drive and not just as an ISO that is reset when you reboot.
- If you don't like using windows.
- If you want a more performant operating system instead of windows, the performance boost is especially notable for older devices.

**Disadvantages of JameOS 1.1?**

- Comes as an .img not .iso file.
- Does not have a dedicated installer and can be tedious to install to disk.
- It is quite large for a Linux system image file.
- Does not support some windows only applications, including some video games and adobe products.
- Does not have a lot of active developers (just me).

## Which Version Should I Use ##

Most likely JameOS 1.1 as it has a desktop and is fully usable for almost anyone and on almost any device. 

## Download Link ##

Click [here](https://drive.google.com/drive/folders/1iHFzuZzZGXZiJaG5aZiTY3S2Jp2bV9zU?usp=sharing "Downloads") for the downloads.

## How To Install ##

**Note: You will need a USB drive you are willing to erase to install JameOS on**

  1. Download the JameOS.img file from the link above.
  
  2. Go to https://rufus.ie/en/(https://rufus.ie/en/ "Rufus") and download it.
  
  3. Now run Rufus.
  
  4. Click "Show advanced drive properties" and check the "List USB Hard Drives" option.
  
  5. Click the box under where it says "device" and select the USB drive you will install JameOS on, this will delete everything on the drive so make sure you've moved everything off of it. 
  
  6. Now click the "SELECT" button and select the JameOS.img file.

  7. Finally click "START" and then "OK".

  8. Once it is done running the green bar at the bottom should be all the way full and say "READY".

  9. Now hold down the shift key while you click the restart button in the start menu.

  10.This should bring up a blue screen with an option called "Use a device", click on that option.

  11.Find the USB option and click it.

  12.Your computer will then turn off and if all goes right and when it reboots it should come up with a blue error screen.

  13.Press enter to select "OK" and then press any key before the reboot.
  
  14.Choose the "Enroll key from disk" option.

  15.Select the option that seems like it is the USB drive.

  16.Select the "JameOS secure boot key.cer" file.

  17.Now choose the "Contine" option and then choose "Yes".

  18.Now choose the "Reboot" option.

  19.From now on you can hold the shift key while you click the restart button and then choose to boot from the USB drive to run JameOS.

  20.To login the default password is "Password".

## Post Install Advice ##

- Change the root password for security reasons:
  1. Type `sudo passwd root` in the terminal and press enter.
  2. Next type the new password twice. (note: you wont see the password as you are typing it)
- Change the user password so people cant loggin to your account:
  1. Open the System Settings application.
  2. Navigate to the Users tab under Personalization.
  3. Make the changes you want to make.
- Resize the partiton in order to get more space on the drive:
  1. First lets open the Partition Manager application, and type our new password.
  2. Once it is open find the partiton labeled JameOS 1.1.
  3. Right click the partition and click the resize/move option.
  4. In this menu there will be a bar at the top, slide the shaded in part of the bar all the way to the right, so it fills up the rest of the space, then click okay.
  5. Now click the button in the far left corner that says Apply.
  6. Finaly click the button says Apply Pending Operations.
  7. Assuming everything went okay it should say All operations successfully finished, now feel free to click OK and close the application.
- Update applications and learn to install new applications:
  1. Open the Add/Remove Software application, it should be located on the taskbar too.
  2. There are three tabs in the top of the application: Browse, Installed and Updates
  3. First lets go to Updates. It will automaticaly check for some updates.
  4. If you wish to update your system, in the bottom right corner click Apply.
  5. Type your password and then it will update everything for you, it may require a restart to apply some updates, but you can still use your computer just fine if you hit close and just restart some other time.
  6. Next we can go to Installed, where we can see installed applications.
  7. Clicking on applications here will allow us to see details about them you can also serch for certain apps using the search button in the top left.
  8. You can delete applications by clicking the trash icons on the main page or the remove button in the details page.
  9. Next click Apply in the bottom right corner and then Apply in the next prompt after.
  10.Next type your password and wait as it uninstalls the application.
  11.Finaly lets go to the Browse tab.
  12.Here you can see all the applications we can install on your system.
  13.Again you can click them the see details of applications and serch for them in the top left.
  14.Once you find an app you want click the down arrow next to it.
  15.Then agin click Apply in the bottom corner and type your password.
  16.It might ask some questions but, you shoudld be good to just press Choose or Apply on any prompt.
  17.Wait for it to install and your good!
- Setup dual boot for easly switching operating systems:
  1. Open the termainl and run `sudo dual-boot`
  2. It will ask you some questions, answer them to the best of your ability and then you should be good.

## Where To Find Help ##

I'm hopeful this project can help you make the switch to Linux. 
Unfortunately however bugs and lack of experience with new software can cause a lot of frustration and lead many users to quit. 
Fortunately There are many great resources for finding help with Linux systems. 
However if you run into some trouble these are some super helpful resources to both look through and ask questions on.

**Some of the resources I find most helpful are listed here:**

- [Arch Linux Wiki](https://wiki.archlinux.org/ "ArchWiki")
- [Arch Linux Forums](https://bbs.archlinux.org/ "Arch Linux Forums")
- [Unix Stack Exchange](https://unix.stackexchange.com/ "Stack Exchange")
- [LinuxQuestions.org](https://www.linuxquestions.org/ "LinuxQuestions.org")

**You can also report problems you face or help you need the in issues tab of this repository or contact me if you are someone I personally know.**

## Upcoming Features ##

These are some other versions of JameOS I would like to release sometime in the future. 

### **JameOS Recovery** ###

**What will it be?**

- This will an added feature or standalone disk image that has useful tools for troubleshooting errors.

**When will it be out?**

- Hopefully soon, after the 1.1 release is more stable.

### **JameOS 1.2** ###

**What will it be?**

- This will be a release based off of JameOS 1.1 but will contain lots of easter eggs and inside jokes.

**When will it be out?**

- When I feel like it.

### **JameOS 1.1-arm** ###

**What will it be?**

- This will be a version of JameOS that works for arm devices, such as the raspberry pi.

**When will it be out?**

- Hopefully soon, once I get all the bugs out of the 1.1 release. 

### **JameOS.sh** ###

**What will it be?**

- It will be a script that transforms any linux system into a JameOS system and automatically installed JameOS on the Arch Linux installer.

**When will it be out?**

- Idk, I might not ever do this.

## How To Support Me ##

I am happy to take any advice people have for this project, most likely just throw it in as an issue and I will see what I can do to help you.



#### **Have a great rest of your day!!!** #### 
