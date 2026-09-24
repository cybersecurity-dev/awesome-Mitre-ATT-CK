<div align="center">

```mermaid
mindmap
  root((MITRE ATT&CK))
    Reconnaissance
      Gather Victim Information
      Active Scanning

    Resource Development
      Infrastructure
      Accounts
      Domains

    Initial Access
      Phishing
      Exploit Public-Facing Apps
      Drive-by Compromise

    Execution
      PowerShell
      Bash
      Command Execution

    Persistence
      Scheduled Tasks
      Startup Items
      Services

    Privilege Escalation
      Sudo Abuse
      Token Manipulation

    Defense Evasion
      Obfuscation
      Packing
      Disable Security Tools

    Credential Access
      Keylogging
      Credential Dumping

    Discovery
      System Discovery
      Network Discovery

    Lateral Movement
      SSH
      RDP
      SMB

    Collection
      Screen Capture
      File Collection

    Command and Control
      HTTP
      HTTPS
      DNS

    Exfiltration
      Cloud Storage
      Encrypted Channel

    Impact
      Data Destruction
      Disk Wipe
      Ransomware
```

# **`Awesome`** [MITRE](https://www.ibm.com/think/topics/mitre-attack) [ATT&CK](https://wikipedia.org/wiki/ATT%26CK) (_Adversarial Tactics, Techniques, and Common Knowledge_) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)]()
[![Windows](https://custom-icon-badges.demolab.com/badge/Windows-0078D6?style=for-the-badge&logo=windows11&logoColor=white)]()
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
flowchart LR

Malware[Malware Sample]

Malware --> Static[Static Analysis]
Malware --> Dynamic[Dynamic Analysis]
Malware --> Hybrid[Hybrid Analysis]

Static --> ATTCK
Dynamic --> ATTCK
Hybrid --> ATTCK

ATTCK --> BehaviorMapping
BehaviorMapping --> Tactics
BehaviorMapping --> Techniques
BehaviorMapping --> Procedures

Tactics --> FeatureEngineering

FeatureEngineering --> ML[Machine Learning]
FeatureEngineering --> DL[Deep Learning]
FeatureEngineering --> GNN[Graph Neural Networks]

GNN --> Detection
ML --> Detection
DL --> Detection

Detection --> ExplainableAI
Detection --> ThreatHunting
Detection --> IncidentResponse
```
## 📖 Contents
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)

##

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-Mitre-ATT-CK/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-mitre-attck-adversarial-tactics-techniques-and-common-knowledge-)
