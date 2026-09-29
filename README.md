# SSH Remote Port Forwarding Lab

## Overview

This lab demonstrates how SSH remote port forwarding can be used to securely access a web server through an SSH connection.

The lab used a Windows virtual machine running XAMPP as the web server and SSH/PuTTY to establish the remote port forwarding tunnel.

## Technologies Used

- Kali Linux
- OpenSSH
- PuTTY
- Windows VM
- XAMPP
- Apache
- SSH Remote Port Forwarding

## Lab Objectives

- Configure a web server using XAMPP
- Verify that the web server works inside the Windows VM
- Configure SSH access
- Configure remote port forwarding using PuTTY
- Establish an SSH connection
- Verify that the forwarded connection works

## Lab Setup

The Windows VM was configured with XAMPP and Apache.

The SSH connection was then used to create a remote port forwarding tunnel between the systems.

## Steps

### 1. Start the XAMPP Web Server

XAMPP was started on the Windows VM and Apache was used as the web server.

[View Screenshot](picture1github.pdf)

### 2. Verify the Web Server

The web server was tested from inside the Windows VM to confirm that Apache was running correctly.

[View Screenshot](githubpicture2.pdf)

### 3. Configure the Firewall

The Windows firewall was checked to demonstrate that external access to the web server was being blocked.

[View Screenshot](github3.pdf)

### 4. Configure Remote Port Forwarding

PuTTY was configured to establish the SSH remote port forwarding tunnel.

[View Screenshot](github4.5.pdf)

[View Screenshot](github4.6.pdf)


### 5. Establish the SSH Connection

An SSH connection was successfully established using the SSH user account created on the host machine.

[View Screenshot](github5.pdf)

### 6. Verify the Tunnel

The final step was testing the connection to verify that the SSH remote port forwarding tunnel was working.

[View Screenshot](github6.pdf)

## What I Learned

Through this lab, I learned how SSH can be used for more than remote login. SSH can also create secure tunnels that allow network traffic to be forwarded between systems.

I also learned how firewall rules can affect access to services and how port forwarding can provide access to a service through an SSH connection.

## Skills Demonstrated

- SSH
- OpenSSH
- Remote Port Forwarding
- PuTTY
- XAMPP
- Apache
- Windows Firewall
- Linux/Windows networking
- Network troubleshooting
