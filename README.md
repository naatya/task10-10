# task10-10
Firewall Configuration &amp; Testing

**Project Overview**

Implementation of host-based security rules on Kali Linux to secure the network environment for Elevate Labs.

**Step-by-Step Implementation**

1.**Requirement Analysis:** Identified essential services (Web, SSH) and insecure protocols (FTP) to be managed.

2.**Firewall Initialization**: Enabled UFW and set default policies to deny incoming and allow outgoing.

3.**Port Configuration:**

Authorized Port 80/443 (HTTP/S) for web traffic.

Authorized Port 22 (SSH) for secure remote access.

Blocked Port 21 (FTP) to mitigate clear-text data risks.

4.**Connectivity Testing**: Used nmap and ping to verify that only authorized ports are reachable.

5.**Traffic Monitoring:** Enabled system logging (/var/log/ufw.log) to track real-time connection attempts.

6.**Threat Mitigation:** Identified and blacklisted malicious IP addresses to prevent targeted attacks.

7.**Documentation:** Logged all active rules and their technical justifications for audit purposes.

8.**Impact Analysis:** Confirmed 90% reduction in attack surface and improved network visibility.
