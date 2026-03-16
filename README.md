# apex_task1
lab setup
Kali lab setup: Creating a Virtual Cybersecurity Lab

The goal of this project was to set up a virtual cybersecurity lab using Oracle VM VirtualBox. In this lab, users can practice penetration testing and network analysis on both an attack machine and a target that is intentionally vulnerable.

Lab Components

Kali Linux is the attacker machine. It is a Linux distribution designed for security testing and cybersecurity research. It includes many security tools such as Nmap, Wireshark, Burp Suite, and Metasploit. These tools assist security professionals in conducting vulnerability assessments or ethical hacking.

Metasploitable2 is the target machine. Metasploitable 2 is a virtual machine that is purposely vulnerable. It allows users to practice penetration tests by exploiting known vulnerabilities and running insecure services. This setup helps students gain experience in system exploitation in a controlled setting.

Virtual Lab Configuration

Both Kali and Metasploitable 2 are installed in VirtualBox and connected through an isolated virtual network. This configuration lets the attacker machine (Kali) communicate with the target machine (Metasploitable 2) without affecting the real network.

Wireshark Capture Test

Network traffic between Kali and Metasploitable 2 was analyzed using Wireshark. The tool captured packets created during the scanning and communication between the machines. These captured packets are useful for observing the interactions between the attacker and the target machines.

Purpose of the Lab

This virtual lab helps learners understand: basic penetration testing concepts, network reconnaissance, packet analysis, safe cybersecurity experimentation in an isolated environment, and the protocol operations for both TCP and DNS. It also covers the TCP three-way handshake.
