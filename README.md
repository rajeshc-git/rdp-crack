<div align="center">

# 🛠️ TermsrvPatcher

### Windows Terminal Services Patch Utility

<img width="100%"  alt="TermsrvPatcher Banner" src="https://github.com/user-attachments/assets/d84064f7-8cd8-4243-b72b-8d563fecfdd8" />
<br/>



![PowerShell](https://img.shields.io/badge/PowerShell-5.1%2B-5391FE?style=for-the-badge\&logo=powershell\&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge\&logo=windows\&logoColor=white)
![Admin](https://img.shields.io/badge/Requires-Administrator-red?style=for-the-badge\&logo=windows-terminal\&logoColor=white)
![Status](https://img.shields.io/badge/Status-Stable-2EA043?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-black?style=for-the-badge)

<br/>

> ⚡ Lightweight PowerShell utility for patching Windows Terminal Services components.

</div>

---

# 🚀 Usage

# Take ownership (powershell run as admin)
```
takeown /f C:\Windows\System32\termsrv.dll /a
```
---
```
icacls C:\Windows\System32\termsrv.dll /grant Administrators:F
```
---

# Bypass policy of powershell
```
Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process
```

---
# Run
```powershell id="h7s82l"
.\TermsrvPatcher.ps1
```

---

# 🛠️ Run as Administrator

1. Press `Start`
2. Search for **PowerShell**
3. Right-click **Windows PowerShell**
4. Select **Run as Administrator**
5. Navigate to the project folder:

```powershell id="w8n19d"
cd "C:\Path\To\TermsrvPatcher"
```

6. Run the script:

```powershell id="y5x22m"
.\TermsrvPatcher.ps1
```

---

# 📦 Requirements

* Windows 10 / 11
* PowerShell 5.1+
* Administrator privileges
* Execution policy allowing script execution

---

# ⚠️ Warning

This script modifies Windows Terminal Services components.

Before running:

* Create a system restore point
* Backup important files
* Temporarily disable antivirus protection if required

---

# 📂 Example

```powershell id="d9q11v"
PS C:\Tools\TermsrvPatcher> .\TermsrvPatcher.ps1
```
---
Optional
# 3. Strip all inherited permissions and restrict Administrators to Full, Authenticated Users to Read-only
```
icacls "C:\Windows\System32\termsrv.dll" /inheritance:r /grant:r "*S-1-5-32-544:(F)" /grant:r "*S-1-11:(R)"
```
---
# 4. Downgrade standard Local Users and All Application Packages to Read-only
```
icacls "C:\Windows\System32\termsrv.dll" /grant:r "*S-1-5-32-545:(R)" /grant:r "*S-1-15-2-1:(R)"
```
---



