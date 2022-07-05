# Sysmon

- [Windows Documentation & Download Link](https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon)
- [Linux Sysmon Download (Github Link)](https://github.com/Sysinternals/SysmonForLinux)

Installation:
```powershell
Download-SysInternalsTools C:\Sysinternals
```
Setup:
```cmd
sysmon.exe -accepteula -i sysmonconfig-export.xml
```

Sample config files in XML: 
- [sysmonconfig-export.xml](sysmonconfig-export.xml) (Credits: SwiftOnSecurity)
- [ion Storm config file](https://github.com/ion-storm/sysmon-config/blob/develop/sysmonconfig-export.xml) (Credits: ION Storm)
