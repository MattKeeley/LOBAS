---
Name: Ilasm.exe
Description: used for compile c# code into dll or exe.
Author: Hai vaknin (lux)
Created: 17/03/2020
Commands:
  - Command: ilasm.exe C:\public\test.txt /exe
    Description: Binary file used by .NET to compile c# code to .exe
    Usecase: Compile attacker code on system. Bypass defensive counter measures.
    Category: Compile
    Privileges: User
    MitreID: T1127
    MitreLink: https://attack.mitre.org/techniques/T1127/
    OperatingSystem: Windows 10,7
  - Command: ilasm.exe C:\public\test.txt /dll
    Description: Binary file used by .NET to compile c# code to dll
    Usecase: A description of the usecase
    Category: Compile
    Privileges: User
    MitreID: T1127
    MitreLink: https://attack.mitre.org/techniques/T1127/
Full_Path:
  - Path: C:\Windows\Microsoft.NET\Framework\v4.0.30319\ilasm.exe
  - Path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ilasm.exe
Code_Sample:
  - Code:
Resources:
  - Link: https://github.com/LuxNoBulIshit/BeforeCompileBy-ilasm/blob/master/hello_world.txt
Acknowledgement:
  - Person: Hai Vaknin(Lux)
    Handle: "@VakninHai"
  - Person: Lior Adar
    Handle:
---
