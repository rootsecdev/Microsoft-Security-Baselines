# Microsoft-Security-Baselines

All baselines are a hybrid mix of Microsoft Security Compliance, CIS, and DISA recommendations. These are unique baselines that draw upon standard practices of all three approaches. They contain the following baselines:

Windows 10 V1803 (RS4)
=================
- Windows 10 RS4 Virtual Smart Card Policies
- Windows 10 RS4 - Computer
- Windows 10 RS4 - BitLocker
- Windows 10 RS4 - Defender Antivirus
- Windows 10 and Server 2016 - Credential Guard
- Internet Explorer 11 - Computer

## Notes:

Windows 10 RS4 Computer baseline will also remediate the following security vulnerabilities

- [Speculative Store Bypass and mitigations around Spectre Variant 2 and Meltdown](https://support.microsoft.com/en-us/help/4073119/protect-against-speculative-execution-side-channel-vulnerabilities-in)

```
reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management" /v FeatureSettingsOverride /t REG_DWORD /d 8 /f
reg add "HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Memory Management" /v FeatureSettingsOverrideMask /t REG_DWORD /d 3 /f
```


Windows Server 2016 Member Server
=================
- Windows Server 2016 - Member Server Baseline - Computer
- Windows 10 and Server 2016 - Credential Guard
- Windows Server 2016 - Member Server Windows Defender
