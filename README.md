[![](https://img.shields.io/badge/NACG_CJanGe-shuttle-purple)](http://github.com/NACG-Mohr/CJan-Ge)
<h2 align="center">SHUTTLE(穿梭机)用于网安常用工具的下载程序 </h2>
熟练使用工具是每个网络安全工程师的必备技能。但每当购进设备，常常会因下载配置工具的繁琐而发愁。SHUTTLE(穿梭机)便能完美的解决这一问题，内收录了大量的常常用工具，免去了挨个去找工具的下载地址的繁琐步骤。于2023年被收录于CJan-Ge
### [# 00x02] 使用：

```bash
.__            __    __  .__
  _____|  |__  __ ___/  |__/  |_|  |   ____
 /  ___/  |  \|  |  \   __\   __\  | _/ __ \
 \___ \|   Y  \  |  /|  |  |  | |  |_\  ___/
/____  >___|  /____/ |__|  |__| |____/\___  >
     \/     \/                            \/

   [01] Information Gathering
   [02] Vulnerability Analysis
   [03] Web Hacking
   [04] Database Assessment
   [05] Password Attacks
   [06] Wireless Attacks
   [07] Reverse Engineering
   [08] Exploitation Tools
   [09] Sniffing and Spoofing
   [10] Reporting Tools
   [11] Forensic Tools
   [12] Stress Testing
   [13] Install Linux Distro
   [14] Termux Utility
   [15] Shell Function [.bashrc]
   [16] Install CLI Games
   [17] Malware Analysis                                                      [18] Compiler/Interpreter
   [19] Social Engineering Tools

   [99] Update the shuttle
   [00] Exit the shuttle

sute > set_install
```
## Feature
- **Tool Installation**  
Install Single Tool  
`sute > set_install 1`  
Install Multi Tool  
`sute > set_install 1 2 3 4`  
Install All Tool  
`sute > set_install @`  
- **Default Dir Install**
On `shuttle.conf` replace symbol ~ with directory you want  
Example: shuttle.conf  
`HOME = /sdcard`
### Requirements
• Python 3.x

#### Installation and Using Lazymux
```bash
apt install python git
git clone https://github.com/nacglalevin/shuttle
python shuttle.py
```