# Microsoft-Security-Baselines

This area is dedicated to security baselines. 

Windows Server 2016 Member Server
=================
The following policies are alterations suggested if using Windows Server 2016 baselines downloaded from the Security Compliance Toolkit download area: https://www.microsoft.com/en-us/download/details.aspx?id=55319

**Enable Oracle Remediation to Force Updates Clients Protection Level**

Computer Configuration > Policies > Administrative Templates > System > Credentials Delegation > Encryption Oracle Remediation

**Disable SMB1 Server**

Computer Configuration > Policies > Administrative Templates > MS Security Guide > Configure SMBv1 Server

**Enable SMB1 Client Driver Disable Driver (recommended)**

Computer Configuration > Policies > Administrative Templates > MS Security Guide > Configure SMB v1 client driver

**Turn off Multicast Name Resolution**

Computer Configuration > Policies > Administrative Templates > Network > DNS Client > Turn off multicast name resolutio

**Disable Netbios**

Computer Configuration > Administrative Templates > MS Security Guide > NetBT NodeType configuration
"P-Node(recommended)"

**Enable Extended Protection for LDAP Authentication (Domain Controllers Only) Enabled, Always (recommended)**

Computer Configuration > Administrative Templates > MS Security Guide > Extended Protection for LDAP Authentication (Domain Controllers Ony) 
