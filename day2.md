

# Day 2 – Internet & Networking Basics

## What is a Server?
A server is a powerful computer or program that provides resources, data, or services to other computers (clients) over a network. It acts as a central hub for sharing information and performing tasks such as:
- Hosting websites
- Managing emails
- Storing files

## How Computers Communicate with Servers
Computers communicate with servers by sending data packets over networks (internet or local) using standardized protocols like TCP/IP.

## Key Networking Concepts

### IP Address
An IP (Internet Protocol) address is like a mailing address for a device or server on the internet. It is a unique string of numbers (e.g., 192.0.2.1) that allows devices to locate and communicate with each other.

### DNS
DNS (Domain Name System) is the internet’s phonebook. It translates human-friendly domain names (like google.com) into IP addresses that computers use to find servers.

### HTTP
HTTP (HyperText Transfer Protocol) is the standard protocol browsers and servers use to request and send web content.

### HTTPS
HTTPS is the secure version of HTTP. It uses SSL/TLS encryption to protect data sent between the browser and the server. It is identified by a lock icon in the browser.

## Network Devices and Their Roles

### Router
- Operates at Layer 3 (Network Layer)
- Directs data packets between networks using IP addresses

### Switch
- Operates at Layer 2 (Data Link Layer)
- Sends data to specific devices within the same network using MAC addresses

### Firewall
- Acts as a security barrier
- Inspects traffic and blocks unauthorized or malicious access

### Modern Networks
Many modern routers combine routing, switching, and firewall functionality into one device.

## Computer Ports

### Physical Ports
Physical ports are the visible connectors on a computer used to connect external devices.

Common types:
- USB / USB-C
- HDMI
- DisplayPort
- Ethernet (RJ-45)
- Audio jacks (3.5mm)
- Thunderbolt
- Legacy ports (VGA, Serial, PS/2)

Key characteristics:
- Used for input and output (I/O)
- Standardized for compatibility
- Different speeds depending on port type

### Logical (Network) Ports
Logical ports are virtual software-based endpoints numbered from 0–65535.
Examples:
- Port 80 → HTTP
- Port 443 → HTTPS

Firewalls use logical ports to control which network traffic is allowed or blocked.

## Simple Network Diagram

Computer → Router → Internet → Cloud Server

### Description
- Computer (Client): The user device
- Router: Connects the local network to the internet
- Internet: The wide area network
- Cloud Server: Hosts services and data (e.g., AWS)

### Data Flow
1. Request leaves the computer
2. Router translates private IP to public IP (NAT)
3. Data travels across the internet
4. Server responds back to the computer
