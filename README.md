# PC Scanner (macOS Version)

**PC Scanner** is an open-source tool that scans your Mac for executable and script files commonly associated with Windows **and** macOS systems.  
It helps you quickly locate files like `.exe`, `.cmd`, `.vbs`, `.app`, `.pkg`, `.sh`, and `.plist` across your file system.

---

## 🔍 What It Searches For

PC Scanner looks for potentially executable or script-related files, including:

- **Windows-related**:
  - `.exe` — Windows executables
  - `.cmd` — Command scripts
  - `.vbs` — VBScript files

- **macOS & Unix-related**:
  - `.app` — macOS applications
  - `.pkg` — Installer packages
  - `.sh` — Shell scripts
  - `.plist` — macOS property list files (often tied to launch agents or startup items)

---

## 🎯 Use Cases

- 📁 Find scripts or installers scattered across external drives
- 🧹 Clean up old software installers or temporary apps
- 🔍 Audit potentially dangerous scripts
- 💻 Discover leftover Windows files on shared or migrated systems

---

## 📄 Example Output

```text
Found 12 matching files:

/Users/you/Downloads/setup.exe  
/Applications/ExampleApp.app  
/Volumes/Backup/install.pkg  
~/Library/LaunchAgents/com.example.agent.plist  
~/Documents/cleanup.sh  
...
