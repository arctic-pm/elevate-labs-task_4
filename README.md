- Setup and Use a Firewall on Linux (UFW)

- Objective:
To configure and test basic firewall rules using UFW (Uncomplicated Firewall) on Linux, allowing or blocking specific types of network traffic.

---

- System Details:
- **OS**: Kali Linux
- **Firewall Tool**: UFW (Uncomplicated Firewall)

---
- Steps Performed:

1. **Checked UFW Status**
2. **Enabled UFW**
3. **Added a rule to block inbound Telnet (Port 23)**
4. **Tested Telnet connection to localhost (should be refused)**
5. **Allowed SSH (Port 22)**
6. **Deleted the test Telnet rule**
7. **Listed and verified the final rule set**

---

- Files Included:
  
- `ufw_commands.txt` – Contains the full list of commands and outputs used during this task.
- `firewall_screenshot_1.png & firewall_screenshot_2.png` - Contains screenshots of the commands used in the task.

---
- Summary:

- Firewalls are essential in regulating traffic in/out of a system.
- UFW makes firewall management simpler on Linux.
- Blocking port 23 (Telnet) improves security due to Telnet's insecure design.
- Allowed port 22 (SSH) to ensure remote access remains open.
- All test rules were removed after verification to maintain a clean configuration.
` – Contains the full list of commands and outputs used during this task.

---
