# LARP-AID 
**A desktop field reference tool for EMS, LEO, and Fire roles in the Greenville Roblox LARP.**
Built for GVFD, BFD, WSP, and OCSO.
![Version](https://img.shields.io/badge/version-v2.2.0-58a6ff?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-brightgreen?style=flat-square)
![Updates](https://img.shields.io/badge/auto--updates-enabled-3fb950?style=flat-square)

---

## 📥 Installation

> Fresh install? This is all you need to do. The app handles all future updates automatically.

1. **Go to the [Releases](../../releases) tab** and download `LarpAID-dist.zip` from the latest release.
2. **Unzip the file** using Windows' built-in extractor, WinRAR, or 7-Zip. Extract it somewhere permanent. Your Desktop or Documents folder works fine.
3. **Run `LARP-AID.exe`** inside the extracted folder. No installer, no setup, no account needed.

> [!WARNING]
> The entire folder must stay together. The `.exe` cannot be moved out on its own, it needs all the other files alongside it.

---

## ⬆️ Upgrading from a Version Prior to v1.7.0

> [!IMPORTANT]
> Auto-updates were introduced in **v1.7.0**. If you are running **v1.6.x or earlier**, your installation cannot update itself. You must perform this one-time manual upgrade to get onto the auto-update track.

1. **Delete your old LARP-AID folder** entirely (the one containing your previous `LARP-AID.exe` and its supporting files).
2. **Go to the [Releases](../../releases) tab** and download `LarpAID-dist.zip` from the latest release.
3. **Unzip and run** `LARP-AID.exe` from the new folder as described in the [Installation](#-installation) section above.

After this one-time reinstall, all future updates will happen automatically on launch.

---

## 📌 Pinning to Taskbar / Desktop

**Taskbar:** Click and drag `LARP-AID.exe` directly onto your taskbar. You can also right-click the taskbar icon while the app is running and select **Pin to taskbar**.

**Desktop shortcut:** Right-click `LARP-AID.exe` → **Send to** → **Desktop (create shortcut)**. Don't copy the `.exe` itself to the desktop, it needs its folder.

---

## 🔄 Automatic Updates

Starting with **v1.7.0**, LARP-AID updates itself. When you open the app, it silently checks GitHub for a newer version. If one is available, it downloads and installs it before the window opens. No prompts, no manual steps.

> [!NOTE]
> Requires an internet connection on launch to check for updates. If you're offline, the app opens normally on whatever version you have.

---

## ✦ What's New in v2.2.0

**New features:**
- 🚨 The Active Call HUD now keeps everything in one place. Decision Tree, Triage, Trauma, ACLS, Serial Vitals, and the Report Writer all open right inside the HUD, fully usable, so you never have to leave your call to look something up.
- 📄 New PCR panel in the HUD: write and copy your full report straight from the call screen.
- ▼ New Hide button: tuck the HUD away while your call and scene timer keep running, then reopen it from the topbar right where you left off.

**Improvements:**
- The HUD panel buttons now stay at the top of the screen, even when scrolling long guides like Trauma.
- 🫁 The Airway guide (OPA vs NPA, BVM vs iGel, RSI procedure) now lives in the Airway tab.

**Bug fixes regarding:**
- Triage assessment showing "BG NaN" when no blood glucose was entered
- Penalty calculator breaking after removing the last charge
- The pin button on decision tree results not working
- Decision tree charge shortcuts highlighting the wrong tab
- Search breaking when your search contained quotation marks

---

## 📜 Changelog

| Version | Highlights |
|---------|-----------|
| **v2.2.0** | 🚨 Active Call HUD upgrade: all tools usable in-HUD · PCR panel · Hide/minimize · Airway guide moved to Airway tab |
| **v2.1.0** | Bug fixes: triage BG tile · penalty calculator · decision-tree pins · HUD shortcuts · search |
| **v2.0.0** | 🪖 Roles tab (Firefighter role) · 🔧 Tools tab · Electrical fire scene card · Water Rescue expansion |
| **v1.9.0** | RSI / Chemical Restraint medications · Airway Guide (OPA/NPA, BVM/iGel) · RSI procedure step-by-step |
| **v1.8.0** | 🔥 Full Fire section (GVFD/BFD) · Scene protocols · Specialized Teams · HazMat reference · Abbreviations |
| **v1.7.0** | Auto-updates · Animal Attacks · Burns & Anaphylaxis expansion · Triage calculator upgrade |
| **v1.6.0** | LEO overhaul · MCI alert mode · Timers tab · Notepad · Report Writer |
| **v1.5.0** | Decision tree fixes · Report Writer improvements · MVC & cardiac scene expansion |
| **v1.4.0** | 4 new scene cards: Diabetic, Pediatric, Burns, Seizure |
| **v1.3.0** | Dark mode fixes · General bug fixes |
| **v1.1.0** | What's New panel added |
| **v1.0.0** | Initial release |

---

## ℹ️ About

| | |
|-|-|
| **Built by** | B6verly |
| **EMS** | GVFD / BFD (Greenville & Brookmere Fire Departments) |
| **LEO** | WSP / OCSO (Wisconsin State Patrol / Outagamie County Sheriff's Office) |
| **Fire** | GVFD / BFD |
| **Platform** | Windows 10/11 x64 |
| **Download size** | ~160 MB |
