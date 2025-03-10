# Nmap
- Nmap (Network Mapper) is a powerful security scanning and network discovery tool used in Kali Linux. It allows you to scan networks, identify hosts, and discover services and operating systems running on them.
Here are some key features of Nmap:
1. Port Scanning: Nmap can scan for open ports on a target host or network. It can detect which ports are open, closed, or filtered.
2. Host Discovery: Nmap can discover hosts on a network by sending various types of packets and analyzing the responses.
3. Service and Version Detection: Nmap can identify the services running on the open ports and attempt to determine their versions.
4. OS Detection: Nmap can attempt to determine the operating system of the target host based on the responses to its scans.
5. Scripting Engine: Nmap supports a scripting engine that allows you to write and execute custom scripts to automate scanning and vulnerability assessment.

  - The latest version of this software as well as binary installers for Windows, macOS, and Linux (RPM) are available from [Nmap.org](https://nmap.org/download.html).
  - For full documentation refer this website [Nmap.org](https://nmap.org/docs.html).

  ### Installation
  - This is an in-built tool in kali linux simply type the command in your kali linux terminal
    ```bash
    nmap
    ```
  - If installation is required then simply go with the following command 
    ```bash
    sudo apt install nmap
    ```
  - For more in-depth compilation, installation and removal notes read the installation guide on [Nmap.org]( https://nmap.org/book/install.html)
  
  ### Usage
  - For default Scanning
    ```bash
    sudo nmap <Target-IP>
    ```
  - To know about the different switches of nmap just simply type the help command:
    ```bash
    sudo nmap -h
    ```
     - Target Specification
   
       
       ![image](https://github.com/user-attachments/assets/49ee5c90-5f3f-4548-bc7a-9d581792b66e)

    - Host Discovery


      ![image](https://github.com/user-attachments/assets/4a8db58b-843b-443e-ad15-517bcd9047a2)

    - Scan Techniques
   

      ![image](https://github.com/user-attachments/assets/4cade0c5-c26e-4820-a40d-ab1b7f6ac1e7)

    - Port Specification & Scan Order


      ![image](https://github.com/user-attachments/assets/3c986c09-37fb-41e4-93e0-975b42a92aa5)


    - Service/Version Detection
   

      ![image](https://github.com/user-attachments/assets/3f6a9afe-6549-4b73-8f32-213fb1d904cb)

    - Script Scan & OS Detection


      ![image](https://github.com/user-attachments/assets/07419b39-5a0b-49e7-bc4d-217cf26b6f60)


    - Timing & Performance


      ![image](https://github.com/user-attachments/assets/a00361c7-b2ad-4f5e-8c4e-cdac95430227)

    - Firewall/IDS Evasion & Spoofing


      ![image](https://github.com/user-attachments/assets/4e39b83b-e5ad-4b36-af67-3015f03b8e92)

    - Output


      ![image](https://github.com/user-attachments/assets/9fc521c0-d25b-4e44-9870-a25544c9fafb)

    
    - Examples


      ![image](https://github.com/user-attachments/assets/f44538b5-ae63-45a3-a3fc-7f2f6e402bd5)





