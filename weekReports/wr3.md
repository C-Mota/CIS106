---
name: Clevis Mota
semester: Spring 23
course: cis106
---

# **Week Report 3**

## **Summary of presentations**

### **Introduction to Linux**

**What is an operating system?**  
An operating system provides all fundamental software features of a computer. An OS enables you to use the computer's hardware providing you the basic tools that make the computer useful. Al of those features relay on the OS's kernel. Other OS features are owed to additional programs that run atop the kernel.

**Aside from a kernel, what other parts make an operating system?**  
In addition to the kernel, an operating system has other essential components, such as device drivers, file systems, user interface, system libraries, security modules, and system utilities. These components work together to create a functional and reliable operating system that supports a variety of tasks and applications. 

**What is a Linux distribution?**  
Distro for short, is a collection of software that includes the Linux kernel and various other components, such as system utilities, applications, and user interface. A Linux distribution is typically assembled by a team of developers who select and package software components into a complete operating system. The distribution is then made available for download or installation on various devices, such as servers, desktops, laptops, and mobile devices. Each Linus distribution may have a different set of software components and configuration options, making it suitable for different use cases and user preferences. Some popular Linux distributions include Ubuntu, Fedora, and Arch Linux.

**What is Ubuntu?**  
A popular Linux distribution that is based on the Debian architecture. It is a free and open-source operating system that is designed to be easy to use and install. Ubuntu is known for its user-friendly interface and comes with a wide range of pre-installed applications, including web browsers, office productivity software, and media players. It is widely used for personal and business computing, and also serves as a popular platform developing software applications. Ubuntu is supported by a large active community of developers and users who contribute to its development, documentation, and support.

**Define the following terms:** 

**Open Source -** Software whose code is available to the public, can be modified, distributed freely, and often developed collaboratively by a community of developers.

**Closed source -** Software whose source code is not available to the public and is typically proprietary. Often developed by a single company, and is usually licensed for usr by end-users with restrictions on how it can be modified and distributed.

**free software -** Software that is available to the public for free, whose source code is open, can be modified and distributed by anyone. Typically licensed in a way that ensures users have the right to use, study, modify, and distribute the software without any significant legal restrictions.  

 **What are the 4 freedoms defined by the free software foundation?**  
 The freedom to run the program as you wish, for any purpose.
 The freedom to study how the program works and to modify it to suit your needs.
 The freedom to redistribute copies so you can help others.
 The freedom to distribute copies of your modified versions to others.

### **The basics of Virtualization**

**What is virtualization?**  
Technology that allows multiple operating systems and applications to run on a single physical machine, known as a host. It creates a virtual environment that emulates a complete computer system, including CPU, memory, storage, and networking resources. Each virtual environment, also known as guest, operates independently of other guests and the host, allowing multiple operating systems to run on the same hardware simultaneously.

**List 3 benefits of virtualization**  
**1. Improved hardware utilization:** Virtualization allows multiple operating systems and applications to run on a single physical machine, improving hardware utilization and reducing the need for additional hardware resources. This can result in cost savings and increased efficiency.

**2. Simplified management and maintenance:** Virtualization can make it easier to manage and maintain IT infrastructure by providing a centralized management interface for virtual machines. This can help reduce complexity, improve scalability, and increased flexibility.

**3. Increased flexibility and agility -** Virtualization can provide greater flexibility and agility in deploying new applications and services. It allows IT teams to quickly and easily create new virtual machines or modify existing ones, without the need for additional hardware or downtime. This can help organizations respond more quickly t changing business needs and opportunities.

**What is a hypervisor?**  
Also known as a virtual machine monitor (VMM), it is a type of software that creates and manages virtual machines (VMs). It allows multiple operating systems to run on a single physical machine by creating a layer of abstraction between the host hardware and the guest operating system. The hypervisor allocates hardware resources, such as CPU, memory, and storage, to each virtual machine, and ensures that they operate independently and securely. There are two types of hypervisors: Type 1 hypervisors run directly on the host machine's hardware, while Type 2 hypervisors run on top of an existing operating system. Hypervisors are used widely in virtualization, cloud computing, and server consolidation, among other applications. 

**What is virtualbox**  
VirtualBox is a free and open-sourced virtualization software that allows users to create and run virtual machines on a host machine. Developed by Oracle, VirtualBox supports a wide range of guest operating systems, including Windows, Linux, and macOS. VirtualBox provides a virtual environment that emulates a complete computer system, including CPU, memory, storage, and networking resources. Designed to be user-friendly and can be used for a variety of purposes, including software development, testing, and experimentation. Supporting advanced features such as snapshotting, which allows users to save and restore virtual machine states, and it can be extended through a plugin system. 

### **Exploring Desktop Environments**

**What is a desktop environment? (Provide 3 examples)**  
A desktop environment is a graphical user interface that provides a complete suite of tools and programs to help users interact with their computer system.
Three examples of desktop environments are:
1. GNOME: a user-friendly, modern desktop environment that is known for its sleek design and customization options.
2. KDE Plasma: a highly customizable and feature-rich desktop environment that offers a lot of flexibility to users.
3. XFCE; a lightweight and fast desktop environment that is ideal for older or less powerful computers. It is known for its simplicity and efficiency.
   
**List 4 common elements of desktop environments**  
1. Taskbar or Dock: A taskbar or dock is a graphical user interface element that displays the currently running applications on your desktop. It allows you to switch between different open applications and also provides quick access to frequently used applications.
2. File Manager: A file manager is a program that allows users to manage files and folders on their computer. It typically includes features like creating, copying, moving, and deleting files and folders, as well as basic file operations like renaming and searching.
3. Desktop Icons: Desktop icons are shortcuts to files, folders, or applications that are placed on the desktop for easy access. Users can click on these icons to open the associated file or application.
4. System Settings: A desktop environment typically provides a settings application that allows users to configure system settings such as display resolution, keyboard layout, language settings, and other system-level preferences. This application allows users to customize the look and behavior of their desktop environment according to their preferences.

**What is Ubuntu’s default desktop environments?**  
The default desktop in Ubuntu is GNOME 3. It is used not only by Ubuntu but also by several other linus distributions, such as Debian, Fedora, Red Hat Enterprise Linux, and Oracle linux. The official GUI for GNOME 3 is called GNOME Shell. GNOME was an acronym for GNUS Network Object Model Environment, but the acronym was dropped because it no longer reflected the vision of the GNOME project.

**What are the official flavors of Ubuntu?**  
The official flavors of Ubuntu are different versions of the operating system that come pre-installed with different desktop environments and software. These flavors are officially recognized by Canonical, the company behind Ubuntu, and they receive support and updates just like the main Ubuntu distribution.

As of Ubuntu 21.10, the official flavors of Ubuntu are:

Kubuntu: comes with the KDE Plasma desktop environment.
Xubuntu: comes with the Xfce desktop environment.
Lubuntu: comes with the LXQt desktop environment.
Ubuntu Budgie: comes with the Budgie desktop environment.
Ubuntu MATE: comes with the MATE desktop environment.
Ubuntu Studio: comes with a collection of multimedia creation tools.
Ubuntu Kylin: comes with the Kylin desktop environment and is designed for users in China.
Each flavor has its own unique look and feel, as well as specific software and tools pre-installed to suit different use cases and preferences.  


### **What is a Shell?**  
**What is Bash?**  
Bash (short for "Bourne-again shell") is a command-line interface (CLI) program for interacting with a computer's operating system. It is a popular Unis shell that provides a text-based user interface for executing commands and scripts on Linux, macOS, and other Unix-based systems. Bash can be used to run commands, navigate directories, manipulate files and directories, and automate task through shell scripts. It is a powerful tool for system administrators, developers, and power users who prefer working with the command line rather than a graphical user interface.

**How do you access the Linux CLI?**  
To access the Linux command-line you can follow these general steps:

**1.** Open a terminal emulator: A terminal emulator is a program that allows you to access the command line. You can usually find it in your Linux distribution's applications menu or by pressing a keyboard shortcut such as Ctrl+Alt+T.

**2.** Enter your login credentials: You will be prompted to enter your username and password. Once you have entered these details correctly, you will be logged in to the command-line interface.

**3.** Use the CLI commands: You can use a variety of commands in the CLI, such as changing directories, creating and deleting files and folders, editing text files, and installing software packages. To learn more about the available commands, you can use the "man" command followed by the name of the command you want to know more about.

**4.** Exit the CLI: When you're done using the command-line interface, you can type "exit" or "logout" to log out of the session and close the terminal emulator window.

**What is a console terminal?**  
A console terminal, or console for short, is a physical device that allows users to interact with a computer system directly, without the need for a graphical user interface (GUI). A console usually consists of a monitor, a keyboard, and sometimes a mouse, and it provides access to a text-based command-line interface (CLI) that enables users to issue commands to the computer.

**What is a terminal emulator?**  
A terminal emulator is a software program that replicates the functionality of a console terminal within a graphical user interface (GUI). It allows users to access the command-line interface (CLI) of a computer system, such as the Linux shell or Windows Command Prompt, without the need for a physical console. A terminal emulator provides a text-based interface within a graphical window that simulates a console terminal, and it allows users to issue commands to the computer using keyboard inputs. Examples of popular terminal emulators include PuTTY, iTerm2, and GNOME Terminal.

**Provide 3 examples of Linux commands**  
**1.**  ls: The "ls" command is used to list the contents of a directory. When you type "ls" followed by a directory name, the command will display the names of all the files and directories in that directory.

**2.**  cp: The "cp" command is used to copy files or directories from one location to another. For example, to copy a file called "file.txt" from the current directory to a directory called "mydirectory," you can type "cp file.txt mydirectory/".

**3.**  sudo: The "sudo" command is used to execute a command with elevated privileges. By using "sudo" before a command, you can execute that command as the root user, which has the ability to perform system-level tasks. For example, to install a package using "apt-get" as the root user, you can type "sudo apt-get install packagename".

### **Managing Software**

**Which command is for updating ubuntu**  
Which command is for updating ubuntu**
To update the installed software packages in Ubuntu, you can use the "apt update" command. This command is commonly used in Debian-based Linux distributions as well. This command requires administrative privileges and should be run with "sudo". To perform an update of Ubuntu, you can execute the following command in the terminal:
<pre><code>
sudo apt update
</code></pre>
Keeping your Ubuntu system up-to-date is essential for ensuring that it is running smoothly and securely. Therefore, it is recommended to run these commands regularly to stay up-to-date with the latest updates and security patches.

**Which command is used for installing software. Provide an example.**   
The "apt install" command is used for installing software packages in Ubuntu and other Debian-based Linux distributions. This command requires administrative privileges and should be run with "sudo". Here's an example of how to use it to install Firefox:
<pre><code>
sudo apt install firefox -y
</code></pre>
This command will install the latest version of Firefox while answering "yes" to any question. 

**Which command is used for removing software. Provide an example.**  
The command used for removing software on Ubuntu is "apt remove". This command uninstalls the specified package from your system. This command requires administrative privileges and should be run with "sudo". Here is an example of how to use this command to remove the Firefox web browser from your Ubuntu system:
<pre><code>
sudo apt remove firefox
</code></pre>
This command will remove the Firefox package from your system. It's worth noting that this command only removes the package files, and any configuration files for the package will be left on the system.

**Which command is used for searching for software. Provide an example.**  

The command used for searching for software on Ubuntu using apt is "apt search". This command allows you to search for packages that match the specified search term. Here is an example of how to use this command to search for the "firefox" web browser:
<pre><code>
apt search firefox
</code></pre>
This command will return a list of all packages that contain the word "firefox" in their name or description. The output will include the package name, a short description, and the version number.

**Definition of the following terms:**  

**Package** - is a collection of software files that are bundled together and distributed as a single unit. Packages can contain executables, configuration files, libraries, and other resources. They are often used for easy installation, upgrade, and removal of software.

**Library** - is a collection of pre-written code that can be used by other programs to perform specific tasks. Libraries can be shared across multiple programs, and they can contain functions, classes, or other components that provide specific functionality.

**Repository** - is a central location where software packages and related information are stored and managed. It is used for version control, collaboration, and distribution of software. A software repository can be public or private and can be hosted on local or remote servers. Users can browse, search, and download packages from the repository. In the case of open source software, contributors can also submit changes and updates to the repository.
