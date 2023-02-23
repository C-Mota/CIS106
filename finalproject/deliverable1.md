---
name: Clevis Mota
course: cis106
semester: spring23
---

# Deleverable 1

> Tutorial can be found [here](https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-22-04)

## Concepts I don't understand:

* Apache: a widely used open-source web server software that is used to deliver web pages over the internet. It was first released in 1995 and is now maintained by the Apache Software Foundation.
* UFW: (Uncomplicated Firewall) is a program used to manage and configure firewall rules on a web server. It helps to protect the server from unauthorized access and attacks, and prevent unwanted traffic from consuming network resources. 
* Server block: also known as virtual hosts, are a feature in web servers that allow multiple websites or domains to be hosted on the same server. They are commonly used to separate different websites, applications, or services that are hosted on a single server.
* a2ensite: a2ensite is a command used in Apache web server to enable a site configuration file for a virtual host. The "a2ensite" command is used to enable a particular site configuration file, which specifies how the web server should handle incoming requests for a particular domain or subdomain.
  

## What is a web server? Hardware and software side
A web server is a computer system that is specifically designed to host and deliver web content and applications to clients. The term "web server" refers to both the hardware and software components that make up the system.

On the hardware side, a web server typically consists of a powerful computer system with sufficient processing power, memory, and storage to handle a large number of simultaneous client requests. The exact hardware configuration will depend on the specific needs of the web server, such as the expected number of users and the amount of data that will be hosted.

On the software side, a web server comprises a suite of software programs responsible for delivering web content to clients. This software usually includes an operating system, web server software such as Apache or Nginx, scripting languages like PHP or Python, and databases like MySQL or PostgreSQL.

## What are some different web server applications?
There are many different web server applications available, each with its own strengths and weaknesses. Some of the most popular web server applications include Apache, Nginx, IIS, and Lighttpd.

### Apache
![apache logo](https://geekflare.com/wp-content/uploads/2019/03/apache_server.jpg) 
The most widely used web server application and is known for its flexibility, performance, and robustness. It supports multiple platforms and a wide range of modules, making it highly customizable.

### Nginx 
![nginx logo](https://geekflare.com/wp-content/uploads/2019/03/nginx-server-804x270.png)
A high-performance web server and reverse proxy that is known for its scalability and efficiency in serving static content. It also supports dynamic content through modules and scripting languages.

### Caddy
![caddy logo](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQM8jWf7KG6lEUUHCNjf0fo0U6CfX6O9xooypY93t59&s)
An open-source web server that is easy to use and configure. It has a simple, declarative configuration format, an integrated automatic HTTPS feature, and a plugin architecture for additional functionality. It's suitable for small to medium-sized websites and applications.

### Lighttpd 
![ighttpd logo](https://geekflare.com/wp-content/uploads/2019/03/lighthttpd-server-281x270.png)
A lightweight web server that is known for its speed and efficiency in serving static content. It supports FastCGI and other scripting languages, making it suitable for serving dynamic content as well.

### Other web server applications 
Node.js, which uses JavaScript to build scalable server-side applications, and LiteSpeed an open-source web server designed to be lightweight and efficient, optimized for serving static content. It's written in C and is best suited for high-performance servers and applications that require low latency and fast response times.

## What is virtualization?
Virtualization is the process of creating a virtual version of a resource, such as a computer system, server, network, or storage device, using software to create multiple virtual versions of a physical resource, allowing the resource to be shared among multiple users, applications, or operating systems. It involves the use of a hypervisor, a software layer installed on a physical server, to create multiple virtual machines (VMs) with their own operating systems, applications, and data that share the underlying physical resources. Virtualization is commonly used in enterprise data centers and cloud computing environments to optimize resource utilization, simplify management and deployment, and improve disaster recovery and business continuity. It is an important technology that enables more efficient use of hardware resources, greater flexibility, and scalability in deploying and managing computer systems and applications.

## What is virtualbox?
VirtualBox is a free and open-source virtualization software application that allows users to run multiple virtual machines on a single physical machine. It can be installed on a variety of operating systems and supports a wide range of guest operating systems, allowing users to create and manage isolated virtual machines with their own operating systems, applications, and data. It includes a range of features such as virtualized hardware devices, shared folders, and networking options, and supports advanced features such as snapshots. VirtualBox is widely used for a variety of purposes, including software development, testing, research, and for running legacy applications on modern hardware.

## What is a virtual machine?
A virtual machine (VM) is a software emulation of a computer system that runs on top of a physical machine. It allows multiple operating systems and applications to run on the same physical machine in an isolated environment. Each virtual machine has its own virtual hardware, including CPU, memory, storage, and network interfaces, and is managed by a hypervisor or virtual machine monitor. Virtual machines can be used for a variety of purposes, including software development, testing, research, running legacy applications, and cloud computing. They provide a secure and flexible environment for running different operating systems and applications on a single physical machine.

## What is Ubuntu Server?
Ubuntu Server is a free and open-source Linux-based operating system designed for server environments. It is maintained and supported by Canonical and comes with a wide range of pre-installed software packages for easy setup and configuration of a server environment. Ubuntu Server can be managed using a command-line interface or graphical user interfaces, and includes support for virtualization technologies and cloud computing features. It is widely used in a variety of server environments, from small businesses to large data centers, and is a reliable, stable, and easy-to-use operating system with a strong community support.

## What is a firewall?
A firewall is a network security device that monitors and controls incoming and outgoing network traffic. It acts as a barrier between a private network and the public internet, preventing unauthorized access and attacks on the network. A firewall can be hardware, software, or a combination of both, and it typically uses a set of rules to determine what network traffic should be allowed and what should be blocked. It can filter traffic based on the source and destination IP addresses, ports, protocols, and other criteria, and can also provide additional security features such as intrusion detection and prevention, virtual private network (VPN) support, and content filtering. Firewalls are an essential component of network security and are widely used in a variety of environments, from small businesses to large enterprises.

## What is SSH?
SSH, or Secure Shell, is a network protocol that provides secure and encrypted communication between two networked devices, typically a client and a server. It is widely used for remote administration and management of servers and other networked devices. SSH allows users to securely log in to a remote system and access a command-line interface or a graphical user interface, and to transfer files securely between systems using SFTP or SCP protocols. It uses public-key cryptography to authenticate clients and servers and to establish a secure connection between them, protecting against eavesdropping and man-in-the-middle attacks. SSH is a versatile and reliable protocol that is used by system administrators, developers, and other IT professionals to manage and maintain networked devices securely and efficiently.

