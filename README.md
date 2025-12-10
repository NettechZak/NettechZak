```
> init_sequence.sh
> Loading modules...
> Homelab... [OK]
> Networking... [OK]
> Photography... [OK]
> Content Creation... [OK]
> Cybersecurity... [in progress]
> _
```
<div align="center">
# **ZakPT** | The Digital Workshop
### `Building the future, one packet at a time.`
[![Website](https://img.shields.io/badge/🌐_Website-nettechzak.github.io-00d9ff?style=for-the-badge)](https://nettechzak.github.io/ZakPT_Website/)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NettechZak)
![Profile Views](https://komarev.com/ghpvc/?username=NettechZak&color=00d9ff&style=for-the-badge)
</div>
---
## `$ whoami`
```bash
zakpt@homelab:~$ cat about.txt
```
**21yo tech enthusiast** exploring homelabs, networking, cybersecurity, photography, and content creation.
I'm a passionate tech enthusiast who loves **building, breaking, and fixing things** in my homelab. What started as a simple Raspberry Pi project has evolved into a **full-scale homelab** with enterprise-grade networking, virtualization, and automation.
I share my journey, mistakes, and solutions through videos and blog posts to help others navigate the complex world of **self-hosting and infrastructure**.
When I'm not tinkering with servers or configuring VLANs, you'll find me exploring **photography**, building custom **mechanical keyboards**, or working on **watercooled PC builds**.
---
## `$ ls -la ~/skills/`
<table>
<tr>
<td width="50%">
### 🌐 **Networking**
```yaml
- VLANs & Subnetting
- pfSense / OPNsense
- UniFi Ecosystem
- DNS & DHCP
```
### 🖥️ **Virtualization**
```yaml
- Proxmox VE
- Docker & Compose
- Kubernetes
- LXC Containers
```
</td>
<td width="50%">
### 💾 **Storage**
```yaml
- TrueNAS / ZFS
- NFS & SMB
- RAID Configurations
- Backup Strategies
```
### 🤖 **Automation**
```yaml
- Home Assistant
- Ansible
- Bash Scripting
- CI/CD Pipelines
```
</td>
</tr>
</table>
---
## `$ cat ~/journey/timeline.log`
<details open>
<summary><b>🎯 Future Goals</b> <i>(2025+)</i></summary>
<br>
Expanding into **cybersecurity content**, building a dedicated security lab with pfSense, Suricata IDS/IPS, and Security Onion. Planning to pursue advanced certifications and contribute more to the **open-source community**.
</details>
<details>
<summary><b>🎥 Content Creator & Community Builder</b> <i>(2024)</i></summary>
<br>
Launched my **YouTube channel and blog**, sharing detailed tutorials on homelab setups, networking configurations, and troubleshooting guides. Built a growing community of tech enthusiasts who learn from my successes and failures.
</details>
<details>
<summary><b>🏢 Enterprise-Grade Infrastructure</b> <i>(2023)</i></summary>
<br>
Major infrastructure overhaul:
- Deployed **Dell PowerEdge R720 and R730** servers
- Implemented a **3-node Proxmox cluster** with Ceph storage
- Upgraded to **UniFi Dream Machine Pro** with managed switches and APs
- Designed complex **VLAN architecture** separating IoT, guest, management, and production networks
**This is when things got serious.**
</details>
<details>
<summary><b>🏠 Self-Hosting Deep Dive</b> <i>(2022)</i></summary>
<br>
Went all-in on self-hosting:
- **Plex** for media streaming
- **Nextcloud** for personal cloud storage
- **Home Assistant** for smart home automation
- **Pi-hole** for network-wide ad blocking
- **Bitwarden** for password management
Learned Docker Compose, reverse proxies with **Nginx Proxy Manager**, and SSL certificate management with **Let's Encrypt**.
</details>
<details>
<summary><b>💻 First Homelab Build</b> <i>(2021)</i></summary>
<br>
Transformed an old gaming PC into my first dedicated server. Installed **Proxmox VE** and created my first virtual machines. Spent countless nights learning Linux command line and understanding the basics of virtualization.
**This was the moment I realized I wanted to build something bigger.**
</details>
<details>
<summary><b>🍓 The Raspberry Pi Gateway</b> <i>(2020)</i></summary>
<br>
Started with a **Raspberry Pi 4** running Pi-hole and a basic web server. This tiny computer opened my eyes to the world of self-hosting and network administration. Learned about DNS, DHCP, and basic networking concepts.
**The seed was planted.**
</details>
<details>
<summary><b>🎮 Custom PC Building</b> <i>(2019)</i></summary>
<br>
Built my first custom gaming PC with a **custom watercooling loop**. Fell in love with the hardware side of technology - cable management, RGB lighting, and optimizing performance.
</details>
<details>
<summary><b>🌱 The Beginning</b> <i>(2018)</i></summary>
<br>
Where it all started: Curiosity about how technology works led me down the rabbit hole. Started tinkering with old computers, learning basic troubleshooting, and discovering the joy of fixing things.
</details>
---
## `$ docker ps -a`
<div align="center">
### 🏠 **The Homelab**
[![Homelab](https://img.shields.io/badge/🔧_View_Full_Specs-Homelab_Dashboard-00d9ff?style=for-the-badge)](https://nettechzak.github.io/ZakPT_Website/homelab.html)
```
CONTAINER ID   IMAGE              STATUS         PORTS                    NAMES
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
a1b2c3d4e5f6   proxmox:latest     Up 247 days    8006/tcp                 proxmox-cluster
b2c3d4e5f6g7   unifi:latest       Up 247 days    8443/tcp, 3478/udp       unifi-controller
c3d4e5f6g7h8   plex:latest        Up 247 days    32400/tcp                plex-media
d4e5f6g7h8i9   nextcloud:latest   Up 247 days    443/tcp                  nextcloud
e5f6g7h8i9j0   pihole:latest      Up 247 days    53/tcp, 53/udp, 80/tcp   pihole
f6g7h8i9j0k1   homeassistant      Up 247 days    8123/tcp                 home-assistant
```
</div>
---
## `$ git log --graph --oneline`
```
* 🎯 Implemented UniFi-style switch modals with interactive port visualization
* ✨ Added glitch typing effects to homepage for enhanced aesthetics
* 🔧 Enhanced network topology with clickable nodes and detailed modals
* 📝 Expanded journey timeline with comprehensive milestones
* 🎨 Refined loading screen with smooth logo animations
* 🏠 Built interactive homelab dashboard with real-time monitoring
* 📸 Launched photography section showcasing creative work
* 🔐 Started cybersecurity learning journey and lab setup
```
---
## `$ neofetch`
<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=NettechZak&show_icons=true&theme=transparent&hide_border=true&title_color=00d9ff&icon_color=00d9ff&text_color=ffffff&bg_color=0d1117" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=NettechZak&theme=transparent&hide_border=true&ring=00d9ff&fire=00d9ff&currStreakLabel=00d9ff&background=0d1117" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NettechZak&layout=compact&theme=transparent&hide_border=true&title_color=00d9ff&text_color=ffffff&bg_color=0d1117" width="48%" />
</div>
---
## `$ curl -s https://zakpt.dev/links`
<div align="center">
[![Website](https://img.shields.io/badge/🌐_Website-Visit_My_Site-00d9ff?style=for-the-badge)](https://nettechzak.github.io/ZakPT_Website/)
[![YouTube](https://img.shields.io/badge/📺_YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com)
[![Twitter](https://img.shields.io/badge/🐦_Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Discord](https://img.shields.io/badge/💬_Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com)
</div>
---
<div align="center">
```
┌─[zakpt@github]─[~]
└──╼ $ echo "Where packets go to die (and be reborn)."
```
**⚡ Exploring the digital frontier ⚡**
<sub>Made with 💙 and countless hours of debugging</sub>
</div>



Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
