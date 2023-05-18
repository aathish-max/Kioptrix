# Kioptrix
The Samba vulnerability "RCE" affects Samba version 2.2.8 and prior. This vulnerability allows for remote root exploitation on various operating systems, including Linux (all distributions), FreeBSD (4.x, 5.x), NetBSD (1.x), and OpenBSD (2.x, 3.x, and 3.2 non-executable stack).

The exploit, known as "sambal.c," specifically targets Samba boxes by sending a netbios name packet to port 137. If the box responds with the MAC address 00-00-00-00-00-00, it is likely running Samba and vulnerable to this exploit.

To set up the payload for this exploit, you can use the Searchploit tool. First, copy the exploit file "10.c" from the appropriate location, such as "/usr/share/exploitdb/exploits/multiple/remote/," to your desired directory, for example, "/home/whitedevil."

After setting up the payload, you need to configure it according to your specific target environment and requirements.

Running the exploit successfully would grant direct access to the 'root' user, providing the attacker with full administrative privileges on the compromised system.

Please note that exploiting vulnerabilities without proper authorization is illegal and unethical. This information should only be used for educational and research purposes in a controlled and legal environment.
