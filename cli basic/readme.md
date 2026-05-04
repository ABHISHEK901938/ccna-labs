# IOS CLI Basics Lab

## 📌 Objective
To understand and practice basic Cisco IOS CLI commands and navigation between different modes.

## 🧠 Concepts Used
- User EXEC mode
- Privileged EXEC mode
- Global Configuration mode
- Interface Configuration mode
- Command shortcuts
- Configuration saving and backup

## 🔑 Key Commands
- enable → Enter privileged mode
- disable → Exit privileged mode
- configure terminal → Enter global config mode
- hostname R1 → Change device name
- interface g0/0 → Enter interface config
- do show ip interface brief → Run show command from config mode

## 🔍 Verification Commands
- show ip interface brief
- show running-config
- show startup-config

## 💾 Backup Methods
- copy running-config startup-config
- copy running-config flash:
- copy running-config tftp:

## 📈 Outcome
Successfully navigated IOS CLI modes, configured basic settings, and saved/backed up configurations.

## 🚀 Real-World Use
Network engineers use these commands daily to:
- Configure routers and switches
- Troubleshoot network issues
- Backup configurations for recovery

## 💬 Interview Explanation (10 sec)
Cisco devices have different CLI modes like user, privileged, and configuration mode. We use these modes to configure devices, verify status, and save or back up configurations.