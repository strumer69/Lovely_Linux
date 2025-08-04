# Lovely_Linux
* you can find update training materials here:
* https://learning.lpi.org/en/
* ## linux Essentials:
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
## 1.2 Major Open Source Applications
### software packages:
* **Debian**, **Ubuntu** and Linux **Mint **use the **dpkg**, **apt-get** and apt tools to install software packages
* Red Hat, Fedora and CentOS use the **rpm, yum and dnf** commands instead
* --example:-->sudo apt-get install figlet
### package removal:
*  apt-get remove package_name
*  PAGE 31/442
