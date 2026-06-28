# 4.-Lateral-Movement
Explored lateral movement techniques using impacket tools (psexec, wmiexec, smbexec) to pivot between compromised hosts. Attenmted to connect from Kali into a Windows VM with Administrator credentials. Faced authentication and errors, documenting the troubleshooting process and firewall/service requirements.

# Work Done
- Scanned network with nmap to identify target hosts
- verified connectivity with ping
- Enabled Administrator account and st password on Windows VM
- Tested SMB login with smbclient
- Attempted lateral movement using Impacket (psexec, wmiexec, smbexec)
- Encountered "Guest login" and "Access denied" errors during execution

# Key Learnings
- Lateral movement requires valid Administrator credentials and correct domain/workgroup format
- Windows firewall settings (File & Printer sharing, remote service mgmt) must be enabled gor remote execution
- Diffenrnt Impacket tools (psexec, wmiexec, smbexec) use varied methods; success depends on target configuration
