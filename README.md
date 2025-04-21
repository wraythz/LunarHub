# LunarHub
![LunarHub](https://github.com/user-attachments/assets/edd1d78f-5adc-4076-b4f6-169413d06660)

This is just some batch file that I decided to make in school, then just decided to work on it more

# How to Use:
Run the .exe lmao

# Where's the source code?
In the discord (Not released yet, not my fault if you think this is a RAT lmao)

# Why does VirusTotal mark this as Trojan?
I am not fully sure, but here are some reasons:
- IP Lookup utilizes PowerShell to look up external IP Addresses.
- When a paste is created, it opens a text file, which is often used in ransomware.
- Writes process memory, since it's a batch script, but it isn't recognized as one since it's an executable file.
- Edits registry key, because it needs to set values for variables
- Gathers IP Information to output information to the "About" module
- Attempts to interact with storage devices so it can store the temporary files required (Example: paste.txt)
