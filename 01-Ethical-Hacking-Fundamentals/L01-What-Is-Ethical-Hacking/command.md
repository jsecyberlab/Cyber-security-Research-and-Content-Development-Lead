L01: What Is Ethical Hacking - Commands
This is an introductory lesson so there are no practical commands to run yet.

Commands You'll Learn Later

| Command | What It Does | Lesson |

| `nmap -sV target` | Version detection | L11-L12 |
| `netdiscover -r 192.168.1.0/24` | ARP discovery | L15 |
| `wireshark` | Packet capture | Future |

How I'll Document Commands

For future lessons, commands will be documented like this:

```bash
 Command
nmap -sV -p- target_ip

Expected output
PORT     STATE SERVICE    VERSION
22/tcp   open  ssh        OpenSSH 7.4

What it means
Version detection helps identify potentially vulnerable software versions.

