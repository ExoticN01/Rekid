## RektSploit

# UI
![alt text](https://media.discordapp.net/attachments/688953317568806933/806336858953875457/UICapture.PNG)

# About
This is a Roblox Exploit use LuaU ByteCode Conversion to achieve execution.
The Auto-Updating System Take the Calling Convention and the Adresse itself by string and AOB and put it into a file to store it. 
After, it get it from the file and run it to make the exploit working.

# Credits
- Sloppey - MsgBoxHook
- TheDoomed (Celery) - EyeStep

# Updates
### DLL
- Added SetSimulationRadius
- Added SetHiddenProperty
- Added GetGC
- Added GetHiddenProperty
- Added IsHiddenProperty
- Added SetScriptable
- Added NewCClosure
- Added GetFFlag
- Added SetFFlag
- Added GetThreadIdentity
- Added SetThreadIdentity
- Added FireProximityPrompt
- Added GetRenv
- Added MessageBox
- Added Init Script
- Added GetNameCallMethod Auto-Updating
- Fixed MessageBox
- Fixed HttpGetAsync
- Fixed GetNameCallMethod
- Fixed FireClickDetector
- Fixed HttpGet
- Fixed GetObjects
- Fixed WriteFile
- Fixed Anti-Ban
- Fixed TrustCheck
- Fixed some issues with Auto-Updating
- Updated FireClickDetector
- Better Stability
- Improvement Auto-Updating
- Fixes a Lot of Bugs
### UI
- Added Settings Tab
- Added TopMost Setting
- Added Ads Setting
- Added Discord Rich Presence
- Added Script Tabs
- Added Debug Option
- Fixed Script List
- Fixed Setting Window
- Fixed Bugs
- Changed Color

# Release
- February - June 2021

# Status
- UI -] 80%
- DLL -] 95%

# Documentation
#### File
- [void] writefile([string] Message, [string] Path)
- [void] appendfile([string] Message, [string] Path)
- [string] readfile([string] Path)
- [bool] isfile([string] Path)
- [bool] isfolder([string] Path)
#### Script
- [void] loadstring([string] Script, [string] chunkname)
- [string] HttpGet([string] Url)
- [Asset] GetObjects([string] AssetID)
#### Clipboard
- [void] toclipboard([string] Message)
- [string] getclipboard()
#### Table
- [table] getrawmetatable([Object] Object)
- [void] setrawmetatable([Object] Object, [Table] Table)
- [void] setreadonly([table] Table, [bool] ReadOnly)
- [bool] isreadonly([table] Table)
- [void] make_writeable([table] Table)
- [void] make_readonly([table] Table)
#### Closure
- [void] hookfunction([void] HookedFunction, [void] ReplaceFunction)
- [bool] iscclosure([void] Function)
- [bool] islclosure([void] Function)
#### Console
- [void] createconsole([string] Title)
- [void] closeconsole()
- [void] printconsole([string] Message)
#### Signal
- [void] fireclickdetector([ClickDetector] Detector)
#### Environment
- [void] getgenv()
- [table] getreg()
- [table] getrenv()
- [bool] checkcaller()
- [bool] REKTSPLOIT_LOADED
- [table] getgc()
#### Encryption
- [string] Encrypt([string] Message, [string] Key)
- [string] Decrypt([string] Message, [string] Key)
#### Namecall
- [string] getnamecallmethod()
- [void] setnamecallmethod([string] NameCall)
#### Random
- [string] randomstring([int] Lenght)
- [int] randomint([int] MaxValue)
#### Flag
- [string] getfflag([string] Flag)
- [string] setfflag([string] Flag, [string] Value)
#### Property
- [void] setscriptable([Instance] Object, [string] Property, [bool] IsScriptable)
- [bool] ishiddenproperty([Instance] Object, [string] Property)
- [void] sethiddenproperty([Instance] Object, [string] Property, [global] Value)
- [object] gethiddenproperty([Instance] Object, [string] Property)
- [void] setsimulationradius([int] SimulationRadius, [int] MaxSimulationRadius)
#### Identity
- [int] getthreadidentity()
- [void] setthreadidentity([int] Level)
#### Others
- [int] messagebox([string] Caption, [string] Text, [int] Button)
#### Lib
- MouseLib
#### Upcoming
- firetouchinterest (Soon)
- getconnections (Soon)
- Drawing Lib (Soon)
- Debug Lib (Soon)
- Bit Lib (Soon)

# FAQ
#### Why i do this?
- Because it great to do an exploit without key system and i wanted to make my own and give for free to people who can discover exploiting.
#### Do it have key System?
- No, because key system do not offer a good user experience but you will be able to enable it to finance the project (1 link).
#### Do this is a Virus?
- No, This is totally safe to use.
VirusTotal:
- (UI): https://www.virustotal.com/gui/file/5d9233ae417cffb9e56831fc2d34cf4316b050fe1adfd2f7b5234fd4f2ce1055/detection
- (DLL): https://www.virustotal.com/gui/file/a0683c3ad9a4dc9770df353d0b678fe420e00bbe86a3bdf7aa374ed65bc39873/detection
- (Injector): https://www.virustotal.com/gui/file/b56b550cc305a2fbdebd05d07b81b4647ad35571dc19f3b16154326aea2196cd/detection

#### How Long the Update Take?
- This Exploit is Auto-Updating (5 sec) or take 1 to 12 hours. (INFORMATION: some custom function need to be updated manually)
#### Does it have Anti-Ban
- Yes, It will destroy your logs and wont Upload it (Beta).

# Fix
#### Injecting Issue
...
#### UI Issue
##### Not Opening
- Probably the server is offline or the host. If persist, redownload it. If not working, Report it as a bug.
#### Execution Issue
##### Crashing at Execution 
- Restart Roblox And The Exploit (Task Manager -] RobloxPlayerBeta.exe -] kill) and Retry. If not working, Report it as a bug.
##### Crashing When using custom function 
- Restart Roblox And The Exploit (Task Manager -] RobloxPlayerBeta.exe -] kill) and Retry or, wait for the dev to update it. If not working, Report it as a bug.

# Contact
Discord: Error 404#5600

Discord Server: https://discord.gg/9dpxJ9ZUjy

Website: ...
