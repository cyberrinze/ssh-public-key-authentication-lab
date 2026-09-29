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

![XAMPP Running](screenshots/01-xampp-running.png)

### 2. Verify the Web Server

The web server was tested from inside the Windows VM to confirm that Apache was running correctly.

![Web Server](screenshots/02-web-server-vm.png)

### 3. Configure the Firewall

The Windows firewall was checked to demonstrate that external access to the web server was being blocked.

![Firewall](screenshots/03-firewall-blocking.png)

### 4. Configure Remote Port Forwarding

PuTTY was configured to establish the SSH remote port forwarding tunnel.

![PuTTY Port Forwarding](screenshots/04-putty-port-forwarding.png)

### 5. Establish the SSH Connection

An SSH connection was successfully established using the SSH user account created on the host machine.

![SSH Login](screenshots/05-ssh-login.png)

### 6. Verify the Tunnel

The final step was testing the connection to verify that the SSH remote port forwarding tunnel was working.

![Tunnel Working](screenshots/06-tunnel-working.png)

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
