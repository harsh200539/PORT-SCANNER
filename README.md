# 🔍 Port Scanner – What It Is and How It Works

A **Port Scanner** is a software tool or program used to test a host or server for open, closed, or filtered network ports. Ports are virtual endpoints used by computers to establish network connections and run various services. Each port is associated with a specific application or protocol, such as port 80 for HTTP or port 443 for HTTPS. A port scanner helps determine the status of these ports to understand what services are running and how they are configured.

Port scanners are commonly used by network administrators to diagnose network and connectivity issues. For instance, if a website is not loading, scanning port 80 (used by web servers) can help check whether the server is listening for incoming connections. Similarly, system administrators can use port scanning tools to verify firewall rules, detect misconfigurations, or monitor for unauthorized services.

## ⚙️ How It Works

The way a port scanner works is relatively straightforward: it sends a network request (typically using TCP or UDP) to a target IP address and port number. Based on the response—or lack of one—it determines the port’s status:

- 🟢 **Open**: The port is accepting connections, and there is a service actively listening.
- 🔴 **Closed**: The port is reachable, but no service is running.
- 🟡 **Filtered**: The port is protected by a firewall or security rule that blocks scanning attempts.

## 🛡️ Security Implications

While port scanning is a legitimate and valuable tool for system security and maintenance, it is also widely used by attackers. Malicious actors use port scanners to map out a network’s attack surface, identify vulnerable services, and plan exploits. This dual-use nature makes it essential for defenders to regularly perform their own scans and stay aware of potential exposure.

This project explores how port scanners operate, with examples and implementation details that highlight both their utility and their role in cybersecurity.
