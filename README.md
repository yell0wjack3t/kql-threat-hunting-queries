# KQL Threat Hunting Queries

This repository contains **annotated Kusto Query Language (KQL) queries** developed during hands‑on threat hunting investigations on the [KC7 Cyber](https://kc7cyber.com) platform. [View My Profile Here](https://kc7cyber.com/profile/7c6e70f5)

Each query includes:
- **Hypothesis** – What attacker behavior I was looking for.
- **MITRE ATT&CK mapping** – Technique ID and name.
- **Annotated logic** – Why each filter and join is used.
- **Sample output** – What results look like.

## 📂 Investigations

| Investigation | Description | MITRE Techniques |
|---------------|-------------|------------------|
| [Rap Beef](investigations/rap-beef.kql) | Ransomware deployed via malicious Excel macro | T1204.002, T1059.001, T1486 |
| Valdorian Times | Credential harvesting & lateral movement | *Coming soon* |
| Frognado in Valdoria | Emotet infection chain | *Coming soon* |
| Jojo's Hospital | PowerShell exfiltration | *Coming soon* |
| AzureCrest | C2 beaconing & persistence | *Coming soon* |

## 🛠️ How to Use

These queries are written for **Microsoft 365 Defender / Azure Sentinel**.  
Adjust table names (`DeviceProcessEvents`, `DeviceNetworkEvents`, etc.) and time ranges as needed.

## 📬 Contact

Ashik Arif – [LinkedIn](https://linkedin.com/in/ashikarif)  
🔗 More projects: [github.com/yell0wjack3t](https://github.com/yell0wjack3t)
