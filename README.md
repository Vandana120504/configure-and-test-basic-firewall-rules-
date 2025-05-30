# 🔐 Cyber Security Internship – Task 4: Setup and Use a Firewall

## 📝 Task Description

The goal of this task is to configure and manage basic firewall rules on a Linux machine using UFW (Uncomplicated Firewall). The task demonstrates how to block/allow specific network traffic based on port numbers and verify the results, helping us understand how firewall rules protect systems from unauthorized access.

---

## 🛠 Tools Used

- Operating System: Kali Linux (VirtualBox)
- Firewall Tool: UFW (Uncomplicated Firewall)
- Utilities: telnet, nmap

 Commands Used
 Update repositories and fix key errors (if needed)
sudo apt update
sudo apt install ufw

 Enable UFW
sudo ufw enable

 Check status
sudo ufw status verbose

 Block inbound traffic on port 23 (Telnet)
sudo ufw deny 23

 Allow SSH on port 22 (optional)
sudo ufw allow 22

 Delete the Telnet block rule
sudo ufw delete deny 23

Final rules check
sudo ufw status numbered


![outputt](https://github.com/user-attachments/assets/9fe3cbf8-5139-47f6-bed2-3a1888ab8511)
![out put](https://github.com/user-attachments/assets/8dadd369-383c-43e2-83d4-15fe0c44d97e)

