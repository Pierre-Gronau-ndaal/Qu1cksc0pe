# Qu1cksc0pe
Quick suspicious file analysis tool.

- Usage before install: ```python3 qu1cksc0pe.py --file suspicious_file --category anything```
- Usage after install: ```qu1cksc0pe --file suspicious_file --category anything```

# Screenshot
![Screen](Screenshot.png)

# Categories
- <i>Registry, File, Network, Web, Keyboard/Keylogger, Process<br>
     Dll, Debugger Indentifying, System Persistence, COM Object<br>
     Data Leakage, Other, All</i><br>
<b>Usage</b>: ```qu1cksc0pe --file suspicious_file --category all```

# Scan arguments
<b>----Metadata----</b><br>
<b>Usage</b>: ```qu1cksc0pe --file suspicious_file --metadata```<br><br>

<b>----DLL----</b><br>
<b>Usage</b>: ```qu1cksc0pe --file suspicious_file --dll```<br><br>

<b>----VirusTotal----</b><br>
<b>Attention!</b><i> this argument needs VirusTotal api key.</i><br>
<i>To get your api key go to the VT website</i>: <b>https://www.virustotal.com/</b>

<b>Usage</b>: ```qu1cksc0pe --file suspicious_file --vtscan```
