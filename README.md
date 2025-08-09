# Lovely_Linux
* you can find update training materials here:
* https://learning.lpi.org/en/
* ## linux Essentials:
* ### ------------------------------------------------------------------------------------------------
* ## 1.1 - lesson 1
* ###  introduction
* this seems to be the first chapter of learning linux. in the folowing I will write notes from this section.
* the version I used to learn is 1.6 --> Aug 2025
* ### Distributions:
* **distribution** --> refering to the family of linux systems they belong to. forexample **Debian**  with (deb) format --> this family uses **dpkg** package manager to install and update the applications and packages.
* we have more than one debian base distribution. forexample:
* - Debian GNU/Linux
  - Ubuntu
  - Red Hat (abreviation: RHEL) -->Some of its components require fee-based subscriptions or licenses. All Red Hat based distributions use the package format **rpm**.
* Also;
* SUSE --> germany since 1992
* OpenSUSE -->2004
### Embeded systems:
* combination of computer hardware and software designed to have a specific function --> famous example --> android
* ### android:
* --> refer to pdf1 for more datail.-->page 15/442
* ### Raspberry Pi:
* -->  refer to pdf1 for more datail.-->page 15/442
* ### Linux and the Cloud:
* -->  As of 2017 reports, Linux runs **90%** of the public cloud workload
* - Amazon Web Services(**AWS**) 
  - Google Cloud Platform (GCP), offers different forms of Linux.
  - Even Microsoft offers Linux-based virtual machines in their **Azure** cloud today.
  * Infrastructure as a Service (**IaaS**) -->Linux is usually offered as part of Infrastructure as a Service (IaaS)
### Guided Exercises:
#### 1. How is Debian **GNU/Linux** different from **Ubuntu**? Name two aspects.
* Ubunto is based on **snapshot** ob Debian. so there will be similarities between them.
* **Ubuntu** is recomended for beginners. **Debian** is for more adcanced users.
* main difference is the **complexity** of user configuration. Also **Debian** is more stable compared to **Ubuntu**.  because Debian receives fewer updates that are tested in detail 
#### 2. What are the most common environments/platforms Linux is used for? Name three different environments/platforms and name one distribution you can use for each.
* environments/platforms: **smartphone**, **desktop** and **server**
* Distribution:
- SmartPhone: Android
- Desktop and server--> any distribution that is mostly suitable with the functionality of that machine from **Debian, Ubuntu** to **CentOS and Red Hat** Enterprise Linux.   
#### 3. You are planning to install a Linux distribution in a new environment. Name four things that you should consider when choosing a distribution.
* cost
* performance
* stability
* scalability
#### 4. Name three devices that the Android OS runs on, other than smartphones.
* smart watch, smart TV,  Auto , ...
#### 5. Explain three major advantages of cloud computing.
flexibility, low cost , easy to implement andscale, Back up and recovery, ...
   
    
### Explorational Exercises
#### 1. Considering cost and performance, which distributions are mostly suitable for a business that aims to reduce licensing costs, while keeping performance at its highest? Explain why.
* --> refr to pdf for answers

#### 2. What are the major advantages of the Raspberry Pi and which functions can they take in -business?
* --> refr to pdf for answers

#### 3. What range of distributions does Amazon Cloud Services and Google Cloud offer? Name at least three common ones and two different ones.
* --> refr to pdf for answers

### Summary
* In this lesson we learned:
• What **distributions** does Linux have
• What are Linux **embedded** systems
• How are Linux embedded systems used
• Different applicabilities of **Android**
• Different uses of a **Raspberry Pi**
• What is **Cloud** Computing
• What role does Linux play in cloud computing
### ------------------------------------------------------------------------------------------------
## 1.2 Major Open Source Applications
## Summary
In this lesson, you learned:
• The package management systems used in major Linux distributions
• Open source applications that can **edit** popular file formats
• The server programs underlying many important Internet and local network services
• Common programming languages and their uses
### software packages:
* **Debian**, **Ubuntu** and Linux **Mint **use the **dpkg**, **apt-get** and apt tools to install software packages
* Red Hat, Fedora and CentOS use the **rpm, yum and dnf** commands instead
* --example:-->sudo apt-get install figlet
### package removal:
*  apt-get remove package_name
*  PAGE 31/442
### Data Sharing:
* Between Linux machines, **NFS** (Network File System) is often used.
### programming language:
* **source** code--> for example hello.cpp is a source code
* it should change to a **binary** file in order to be executable --> **compiler** do this for us
* in **interpreted** language, an **interpreter** reads the source code and executes its instruction every time the program is run --> JavaScript, Perl, Shellscript, Python and PHP
-  this makes the **development** easier and faster. but the program itself is slower than compiled programs.
* compiled programs example: C and Java
* page37/442
### Guided Exercises:
* 1-For each of the following commands, identify whether it is associated with the Debian packaging system or the Red Hat packaging system:
-  dpkg --> deb
-  rpm --> RH
-  apt-get --> deb
-  yum -->RH
-  dnf --> Deb
*  2. Which command could be used to install **Blender** on Ubuntu? After installation, how can the program be executed?
-  --> das ist  gans Einfach--> apt-get install blender  

3. Which application from the LibreOffice suite can be used to work with **electronic spreadsheets**?
   
-  calc
4. Which **open-source web browser** is used as the basis for the development of Google Chrome?
   -   Chromium
   
5. SVG is an open standard for vector graphics. Which is the most popular application for **editing SVG files** in Linux systems?
-  Inkscape
6. For each of the following file formats, write the name of an application able to open and edit the corresponding file:
  -  png --> Gimps
  -  doc --> LibreOffice Writer
  -  xls --> --> LibreOffice Calc
  -  ppt --> LibreOffice Impress
  -  wav --> Audacity
7. Which software package allows file sharing between Linux and Windows machines over the local network?
  - --> samba
### Explorational Exercises
1. You know that** configuration files** are kept even if the associated package is removed from the system. How could you automatically remove the package named cups and its configuration
files from a DEB based system?
  - apt-get purge cups
    
2 Suppose you have many **TIFF image** files and want to **convert** them to JPEG. Which software package could be used to convert those files directly at the command line?
  - ImageMagick
3. Which software package do you need to install in order to be able to open **Microsoft Word documents** sent to you by a Windows user?
  - LibreOffice or OpenOffice
### ------------------------------------------------------------------------------------------------
## 1.3 Open Source Software and Licensing
### Summary
* In this lesson you have learned:
-  Similarities and differences between free and open source software (FLOSS)
-  LOSS licenses, their importance and problems
-  Copyleft vs. permissive licences
-  FLOSS business models
-  
* page 47/442
* the meaning of free software--> there is **4 criteria**:
-  freedom to run the program
-  reedom to study how the program works --> we may also change it.
-   freedom of redistribute it to help others.
-   freedom of redistribute our modified version
### Questiones that you may find the answer at this section:
-  whats Copy_left and Copy_right?
-  whats Dual Licence?
-  what is CC (short for Creative Common) Licencing?
* 6 different CC licensing:
-  1-CC BY (“Attribution”)--> refer to book for more detail --> page 52/442
-  2-CC BY-SA (“Attribution-ShareAlike”)
-  3-CC BY-ND (“Attribution-NoDerivatives”)
-  4-CC BY-NC (“Attribution-NonCommercial”)
-  5-CC BY-NC-SA (“Attribution-NonCommercial-ShareAlike”)
-  6-CC BY-NC-ND (“Attribution-NonCommercial-NoDerivatives”)
### Guided Exercises
1. What are — in a nutshell — the “four freedoms” as defined by Richard Stallman and the Free Software Foundation?
-  freedom 0 --> run the software
-  freedom 1 --> study and modify the software (source code)
-  freedom 2 --> distribute the software
-  freedom 3 --> distribute the modified software
-  
2. What does the abbreviation FLOSS stand for?
-   Free/Libre Open Source Software
3. You have developed free software and want to ensure that the software itself, but also all future works based on it, remain free as well. Which license do you choose?
-  GPL version 3

4. Which of the following licenses would you call **permissive**, which would you call **copyleft**?
-   Simplified BSD License -->  permissive
-   GPL version 3 --> copyleft
-   CC BY --> permissive
-   CC BY-SA -->  copyleft
5. You have written a web application and published it under a free license. How can you earn money with your product? Name three possibilities.
- Dual licensing, e.g. by offering a chargeable “Business Edition”
- Offering hosting, service, and support
- Developing proprietary extensions for customers
- 
### Explorational Exercises
1. Under which license (including version) are the following applications available?
-  Apache HTTP Server --> Apache License 2.0
-  MySQL Community Server --> GPL 2
-  Wikipedia articles --> Creative Commons Attribution Share-Alike license (CC-BY-SA)
-  Mozilla Firefox --> Mozilla Public License 2.0
-  GIMP --> GPL 3
2. You want to release your software under the GNU GPL v3. What steps should you follow?
-   refer to book for answer - page 59/442
3. You have written proprietary software and would like to combine it with free software under the GPL version 3. Are you allowed to do this or what do you have to consider?
-  refer to book for answer - page 59/442
4. Why did the Free Software Foundation release the GNU Affero General Public License (GNU AGPL) as a supplement to the GNU GPL?
-  refer to book for answer - page 59/442
5. Name three examples of free software, which are also offered as “Business Edition”, i.e. in a chargeable version.
 -  refer to book for answer - page 59/442
### ------------------------------------------------------------------------------------------------
## 1.4 ICT Skills and Working in Linux
### summary:
* The **terminal** is a powerful way to interact with the system and there are lots of useful and very
mature tools to use in this kind of environment.
* Linux is largely used in the tech industry to offer IaaS, PaaS and SaaS services.
* There are **three main hypervisors** which play an important role in supporting those: Xen, KVM and Virtualbox.
* The **browser** is an essential piece of software in computing nowadays, but it’s necessary to understand some things to use it with **safety**.
* **DNT** is just a way to tell the website that you do not want to be tracked, **but** there is no guarantee on that.
* Private windows are private only to the computer you’re using but this can allow you to escape from cookie tracking exactly because of that.
* **TLS** is able to **encrypt** your communication on the Internet, but you have to be able to recognize when it’s in use.
* Using **strong passwords** is also very important to keep you safe, so the best idea is to **delegate** that responsibility to a **password manager**
* Another way to secure your communication is to sign and encrypt your files folders and emails with GnuPG.
* dm-crypt and EncFS are two alternatives to encrypt whole disks or partitions
* Finally, **LibreOffice** Impress is a very complete open source alternative to Microsoft Powerpoint
* but there are **Beamer** and **RevealJS** if you prefer to create presentations using code instead of GUIs.
* ProjectLibre and GanttProject can be the right choice if you need a Microsoft Project replacement
* -
* for exercises refer to the PDF.

### ------------------------------------------------------------------------------------------------
# Topic 2: Finding Your Way on a Linux System
## 2.1 Command Line Basics
PAGE 80/442
### Summary:
* In this section we learned:
-  Concepts of the Linux shell
-  what is the Bash shell
-  The structure of the command line
-  An introduction to quoting "abcd" , 'abcd'
-  Commands used in the exercises:
* bash --> The most popular shell on Linux computers.
* echo --> Output text on the terminal.
* ls --> List the contents of a directory.
* type --> Show how a specific command is executed.
* touch --> Create an empty file or update an existing file’s modification date.
* hostname --> Show or change a system’s hostname.
### ------------------------------------------------------------------------------------------------
# 2.1 -->Command Line Basics-->  lesson 2
### in this section the followings are covered:
* types of variables --> local and Environment  and How to change local with **export**
* example:
``` c++
$ export greeting=hey
$ echo $greeting world
hey world
$ bash -c 'echo $greeting world'
hey world
```
* PATH --> to find executale files --> for example instead of using (/usr/bin/ls ) , we simple say (ls) and call the executables more easily.
* if we creat a function named my_script, we should add it to the PATH in order to ba able to use it from every  where:--> export PATH="$PATH:~/my_scripts"
* example: --> export PATH="$PATH:~/2024/skill/0-bash" -->  then go to  parent folder (cd ..) --> bash ex4.bash --> you should see the result of this script :)
* page 89/442 -->
* echo $HOME --> to see your home dir
* which ls --> to find where is the location of (ls) --> or  which myfunftion
* page 103/442 --> guided exercises
### ------------------------------------------------------------------------------------------------
# 2.2 Using the Command Line to Get Help 
* page 106/442
* This chapter focuses on methods to access that documentation, with the purpose of getting help --> man , help, info
* locate --> also this chapter is about the **locate** command
* page 113/442
* 

### ------------------------------------------------------------------------------------------------
### ------------------------------------------------------------------------------------------------


