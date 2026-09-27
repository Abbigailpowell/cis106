# Lecture 2 Introduction to Linux Notes

## 1. What is an Operating System?

An **Operating System (OS)** provides all fundemental software featues of a computer this enables you to use the computer hardware providing the basic tools to make the computer useful. These features relay on the OS's kernel and other features are owed to additional programs that run atop the kernel. 

## 2. What is a Kernel?

The **kernel** is the central part of an operating system.It is responsible for managing low-level features of a computer including the managing system hardware, memory allocation, CPU time and program to program interaction..

## 3. Which Other Parts Aside from the Kernel Identify an OS?

Besides the **kernel**, an operating system can be identified by other components that allow users and programs to interact with the computer. 
These include:
- System utilities – Programs that help manage and maintain the system.
- Libraries – Collections of code that applications can use to perform different functions.
- Graphical User interface – The way users interact with the operating system, such as a command-line interface or graphical user interface.
- Command-Line Sheels - This is the way of using computers before the graphical interface is involved
## 4. What is Linux?

**Linux** is an open-source operating system kernel. It was originally created by Linus Torvalds in 1991. Linux is used as the foundation for many different operating systems and is widely used on computers, servers, mobile devices, and other types of hardware.

## 5. What is a Linux Distribution?

A **Linux distribution**, or distro, is a complete operating system built around the Linux kernel. A distribution usually includes the kernel along with system utilities, libraries, software packages, and other tools needed to use the operating system.

Examples of Linux distributions include:
- Debian
- Ubuntu
- Fedora
- Arch Linux

## 6. List at Least 4 Linux Characteristics

Some important characteristics of Linux include:

- Open source – Its source code is available for people to view, modify, and share.
- Multiuser – Multiple users can use the system and have their own accounts and permissions.
- Multitasking – Linux can run multiple programs and processes at the same time.
- Portable – Linux can run on many different types of computer hardware.
- Secure – Linux uses permissions and other security features to control access to files and system resources.
- Customizable – Users can modify and configure many parts of the operating system.

## 7. What is Debian?

**Debian** is a free and open-source Linux distribution. It is developed by a community of volunteers and is known for being stable and having a large collection of available software packages. Debian is also the foundation for other Linux distributions, including Ubuntu.

## 8. List and Define the Different Types of Licensing Agreements

**Licensing agreements** describe how software can legally be used, copied, modified, and distributed. Common types include:

- Proprietary software license – The software is owned by an individual or company, and the license controls how users can use, copy, modify, or distribute it.
- Free software license – Gives users certain freedoms to use, study, modify, and share the software.
- Open-source license – Allows the source code to be accessed and provides permissions for users to modify and redistribute the software according to the license terms.
- Public domain – Software has no copyright restrictions, allowing people to use, modify, and distribute it without the restrictions of a copyright license.

## 9. What is Free Software? Define the 4 Freedoms.

**Free Software** is software that gives users the freedom to use, study, modify, and share the software. The word "free" refers to freedom rather than necessarily meaning that the software costs nothing.

The four freedoms are:
1. Freedom 0 – Use the program: The user has the freedom to run the program for any purpose.
2. Freedom 1 – Study and modify: The user has the freedom to study how the program works and change it to meet their needs. Access to the source code is necessary for this freedom.
3. Freedom 2 – Share copies: The user has the freedom to distribute copies of the software to help others.
4. Freedom 3 – Share modified versions: The user has the freedom to distribute modified versions of the software so others can benefit from the changes.

## 10. What is Virtualization?

**Virtualization** is a technology that allows one physical computer to create and run multiple virtual computers or environments. Each virtual machine can have its own operating system and applications while sharing the physical computer's hardware resources.

There are two general types of virtualization:

- Server-side virtualization – Virtual machines are created and managed on a server. The server provides the hardware resources needed to run the virtual machines, and clients can access those virtual environments over a network.

- Client-side virtualization – Virtual machines are created and run directly on a user's computer. This allows the user to run another operating system or environment on their own device.

Virtualization can also use two types of hypervisors:

- Type 1 Hypervisor – Runs directly on the physical computer's hardware without a traditional host operating system. It is commonly used for servers and data centers.

- Type 2 Hypervisor (Hosted) – Runs on a Host Operating System. It allows users to create and run virtual machines from their regular computer.