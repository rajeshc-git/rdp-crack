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

Run the script in **PowerShell as Administrator**.

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

# 🎨 Custom SVG Banner

Create this file:

```text
assets/banner.svg
```

Paste the following SVG:

```svg id="6pt4rf"
<svg width="1200" height="320" viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>

    <linearGradient id="accent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#58A6FF"/>
      <stop offset="100%" stop-color="#2EA043"/>
    </linearGradient>
  </defs>

  <rect width="1200" height="320" fill="url(#bg)"/>

  <circle cx="150" cy="160" r="70" fill="#58A6FF" opacity="0.15"/>
  <circle cx="1050" cy="80" r="50" fill="#2EA043" opacity="0.15"/>

  <text x="80" y="145"
        fill="white"
        font-size="52"
        font-family="Segoe UI, Arial"
        font-weight="700">
    TermsrvPatcher
  </text>

  <text x="82" y="195"
        fill="#8B949E"
        font-size="24"
        font-family="Segoe UI, Arial">
    Windows Terminal Services Patch Utility
  </text>

  <rect x="80" y="225" width="260" height="10" rx="5" fill="url(#accent)"/>
</svg>
```

---

<div align="center">

### ⭐ GitHub Ready README

Clean • Minimal • Developer Friendly

</div>

