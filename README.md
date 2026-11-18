# NETWORKWALKS-AravindP19-WK2-CYBERSECURITY-PROJECT-REPORT
### Introduction:
This report covers footprinting activities against target domains using multiple OSINTs and local network scanning with Zenmap.

These phases demonstrate how to gather public intelligence to profile a target's web and network infrastructure, uncover publicly exposed data or vulnerable endpoints and map 
the live hosts on a network.
## Footprinting & Network Scanning Phases:
| Field | Detail |
|---|---|
| PenTester Name  | **Aravind P** |
| **Modules completed** | W2-PM4 (theHarvester based Footprinting attacks)<br>W2-PM5 (Zenmap Scanning)<br>W2-PM5-FINAL (Report Writing) |
| **Client/Target** | 1. Microsoft (microsoft.com)<br>2. Public Search Engines (OSINTs)<br>3. Local LAN network |
| **Permission secured from client?** | Yes |
| **Phases covered** | **Phase 1:** Reconnaissance & Footprinting<br>**Phase 2:** Scanning & Network Discovery<br>**Phase 3-5:** Done |

# 1.Disclaimer

Activities were performed only on the systems where I had permission or that I own. For educationa and research purposes only.

# 2. Tools Used

| Tool | Purpose |
|---|---|
| Kali Linux | Operating system used for reconnaissance activities. |
| theHarvester | Gather open-source intelligence(OSINT) such as emails and subdomains. |
| Zenmap(Nmap GUI) | Scan the local subnet to find live hosts, IP addresses, and MAC addresses. |

# 3. Activities Performed

## 3.1 OSINT Footprinting (microsoft.com)

I also utilized **theHarvester** to perform broad OSINT collection against `microsoft.com`.
-   Running `theHarvester -d microsoft.com -l 1000 -b all` revealed missing API keys for services like bevigil, Bitbucket, and BuiltWith,which limited the data sources available.
-   A targeted search using `theHarvester -d microsoft.com -l 1000 -b baidu` yielded no IPs, emails, or hosts from the Baidu search engine.
