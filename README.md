NMAP
**Open ports found are:
  135/tcp open  msrpc
  139/tcp open  netbios-ssn
  445/tcp open  microsoft-ds**
- The port 135/tcp is reported to be open and associated with the msrpc service, which stands for Microsoft Remote Procedure Call (MSRPC)
- Port 139 is associated with the NetBIOS Session Service (netbios-ssn) and is commonly used for SMB (Server Message Block) communication over NetBIOS.
- Port 445 is a TCP port used for Microsoft-DS SMB (Server Message Block) file sharing. This port is often targeted by attackers due to its role in facilitating network resource sharing, which can be exploited for malicious purposes such as ransomware attacks, including the infamous WannaCry and NotPetya incidents
