<div align="center">

### `~/` Security & Networks · Python Developer · CTF Player

[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top_20%25-red?style=flat-square&logo=tryhackme&logoColor=white)](https://tryhackme.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aimen_Khimoum-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aimen-khimoum-315588306/)
[![Portfolio](https://img.shields.io/badge/Portfolio-aimenkhimoum.github.io-00d4ff?style=flat-square&logo=github&logoColor=white)](https://aimenkhimoum.github.io)
[![Mail](https://img.shields.io/badge/Gmail-aimenkhimoum@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:aimenkhimoum@gmail.com)

</div>

---

## `// whoami`

```python
class AimenKhimoum:
    def __init__(self):
        self.name       = "Mohamed Aimen KHIMOUM"
        self.education  = "L2 Informatique — Université Sorbonne Paris Nord"
        self.location   = "Paris, France 🇫🇷"
        self.focus      = ["Offensive Security", "Network Infrastructure", "Python Dev"]
        self.ctf        = {"TryHackMe": "Top 20%", "Root-Me": "active"}
        self.available  = True  # open to internships & apprenticeships

    def bio(self):
        return """
       Passionné par le développement logiciel, le DevOps, le Cloud et la cybersécurité, je construis mon profil
       autour de projets concrets mêlant conception, automatisation et déploiement. J'apprécie particulièrement
       concevoir des applications robustes, orchestrer leur déploiement avec des outils modernes
       et comprendre les infrastructures qui les font fonctionner, du code jusqu'à la production.


        """
```

---

## `// skills`

<table>
<tr>
<td valign="top" width="50%">

### ⚔️ Sécurité Offensive
![Nmap](https://img.shields.io/badge/Nmap-black?style=flat-square&logo=nmap&logoColor=white)
![ffuf](https://img.shields.io/badge/ffuf-111?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![SQLi](https://img.shields.io/badge/SQLi-cc0000?style=flat-square)
![LFI/RFI](https://img.shields.io/badge/LFI%2FRFI-cc0000?style=flat-square)
![Privesc Linux](https://img.shields.io/badge/Privesc_Linux-cc0000?style=flat-square)

### 🐍 Développement & Automatisation
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Scapy](https://img.shields.io/badge/Scapy-009900?style=flat-square)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### 🔐 Sécurité Défensive
![IPS/Firewall](https://img.shields.io/badge/IPS%2FFirewall-cc0000?style=flat-square)
![DPI](https://img.shields.io/badge/DPI-cc0000?style=flat-square)
![iptables](https://img.shields.io/badge/iptables-cc0000?style=flat-square)
![Audit Trail](https://img.shields.io/badge/Audit_Trail-cc0000?style=flat-square)
![ANSSI SecNum](https://img.shields.io/badge/ANSSI_SecNum-003189?style=flat-square)

</td>
<td valign="top" width="50%">

### 🌐 Réseaux & Protocoles
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-0078D4?style=flat-square)
![DNS](https://img.shields.io/badge/DNS-0078D4?style=flat-square)
![VLAN](https://img.shields.io/badge/VLAN-0078D4?style=flat-square)
![TLS](https://img.shields.io/badge/TLS-0078D4?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![tcpdump](https://img.shields.io/badge/tcpdump-0078D4?style=flat-square)

### 🐳 Conteneurisation & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![kubectl](https://img.shields.io/badge/kubectl-326CE5?style=flat-square)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

### 🔭 Veille & Curiosités
![CTF](https://img.shields.io/badge/CTF-Player-blueviolet?style=flat-square)
![OSINT](https://img.shields.io/badge/OSINT-555?style=flat-square)
![IoT Security](https://img.shields.io/badge/IoT_Security-555?style=flat-square)
![CVE Research](https://img.shields.io/badge/CVE_Research-555?style=flat-square)
![AI/ML](https://img.shields.io/badge/AI%2FML-555?style=flat-square)

</td>
</tr>
</table>

---

## `// projects`

<table>
<tr>
<td width="50%" valign="top">

### 🔥 [`Python-IPS-Firewall`](https://github.com/Aimenkhimoum/Python-ips-firewall)
> **Projet phare — Sécurité Réseau**

Système de Prévention d'Intrusion & pare-feu réseau codé en **Python OOP + Scapy**.

- 📄 Politique de sécurité dynamique (`security_policy.json`)
- 🔎 Audit de conformité au démarrage
- 🚀 Analyse **DPI** temps réel sans saturation RAM
- 🛡️ Détection comportementale **DDoS / Flood**
- 🔒 Blocage dynamique via **iptables**
- 📋 Audit Trail complet dans fichier de logs

`Python` `Scapy` `OOP` `DPI` `iptables` `asyncio`

</td>
<td width="50%" valign="top">

### 🔍 [`python-port-scanner`](https://github.com/Aimenkhimoum/python-port-scanner)
> **Outil CLI — Network Recon**

Scanner de ports TCP multi-threadé avec architecture asynchrone optimisée.

- ⚡ Scanning rapide sur grands espaces d'adressage
- ⏱️ Timeouts configurables
- 📊 Export de rapports

`Python` `asyncio` `socket` `CLI`

---

### 🎮 [`Flood-It-C`](https://github.com/Aimenkhimoum/Flood-It-C)
> **Algorithmique — Stratégies comparées**

Implémentation et analyse comparative de stratégies pour résoudre le jeu Flood-It (grille NxN, couleur unique, minimum de coups).

`C` `BFS` `DFS` `Algorithmes`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ♟️ [`Jeu-Morpion-C`](https://github.com/Aimenkhimoum/Jeu-Morpion-C)
> **Moteur de jeu — C**

Moteur de Morpion en C avec matrices 2D et algorithmes de vérification d'état pour la gestion des interactions utilisateur.

`C` `2D Matrix` `Game Logic`

</td>
<td width="50%" valign="top">

### 🐍 [`Jeu-Snake-C`](https://github.com/Aimenkhimoum/Jeu-Snake-C)
> **Structures de données — C**

Snake en C exploitant les **Linked Lists** pour les structures dynamiques. Gestion rigoureuse de la mémoire, prévention active des fuites.

`C` `Linked List` `Memory Management`

</td>
</tr>
</table>

---

## `// certifications`

| # | Certification | Organisme | Date | Compétences clés |
|---|--------------|-----------|------|-----------------|
| 🏦 | **Commonwealth Bank — Software Engineering** | Forage | Mars 2026 | C#, .NET, NoSQL, TypeScript, React |
| 🔴 | **Mastercard — Cybersecurity Simulation** | Forage | Mars 2026 | Cybersécurité, Phishing, Analyse de données |
| ☁️ | **Datacom — Introduction to Cloud** | Forage | Mars 2026 | Cloud, CLI, GitHub Actions, DevOps |
| 🐳 | **Docker For Absolute Beginners** | KodeKloud | Fév. 2026 | Docker, Conteneurisation, Compose |
| ☸️ | **Kubernetes For Absolute Beginners** | KodeKloud | Fév. 2026 | Kubernetes, kubectl, YAML, Pods |
| 🛡️ | **MOOC SecNumacadémie** | ANSSI | Fév. 2026 | SSI, Auth, Sécurité Internet, Nomadisme |

---

## `// ctf & practice`

<div align="center">

| Plateforme | Statut | Focus |
|-----------|--------|-------|
| 🟥 **TryHackMe** | `Top 20%` | Web, Network, Linux, Crypto |
| 🔵 **Root-Me** | `Actif` | Web, Réseau, Système, Forensique |

</div>

```bash
# Domaines pratiqués
khimoum@sec:~$ cat domains.txt

[+] Enumération          → Nmap, ffuf, gobuster
[+] Web Exploitation     → SQLi, XSS, LFI/RFI, IDOR
[+] Privilege Escalation → Linux privesc, SUID, cron jobs
[+] Network Analysis     → Wireshark, tcpdump, packet crafting
[+] Cryptographie        → Hash cracking, encodage, analyse
```

---

## `// stats`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Aimenkhimoum&show_icons=true&theme=github_dark&hide_border=true&title_color=00d4ff&icon_color=00ff88&text_color=c9d8e8&bg_color=0d1117)
&nbsp;&nbsp;
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Aimenkhimoum&layout=compact&theme=github_dark&hide_border=true&title_color=00d4ff&text_color=c9d8e8&bg_color=0d1117)

</div>

---

## `// contact`

<div align="center">

| | |
|---|---|
| 📧 **Email** | [aimenkhimoum@gmail.com](mailto:aimenkhimoum@gmail.com) |
| 💼 **LinkedIn** | [aimen-khimoum-315588306](https://www.linkedin.com/in/aimen-khimoum-315588306/) |
| 🌐 **Portfolio** | [aimenkhimoum.github.io](https://aimenkhimoum.github.io) |
| ⚡ **TryHackMe** | [Profil TryHackMe](https://tryhackme.com) |

> 💡 **Disponible pour des stages et alternances** — toujours partant pour échanger sur des sujets touchant aux réseaux, à l'IoT ou à la sécurité offensive.

</div>

---

<div align="center">
<sub>
⚡ <i>"Comprendre les systèmes en profondeur pour mieux les sécuriser."</i> ⚡
</sub>
</div>
