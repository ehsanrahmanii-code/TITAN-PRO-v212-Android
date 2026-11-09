# TITAN PRO v2.1.2 GLASS-AUTOPILOT — Android APK

TITAN PRO Clean **Glass UI + Autopilot + Learning + Governor** as a **self-contained Android APK**.

- Full modular Flask engine (numpy, pandas, flask, waitress) bundled via **Chaquopy**
- Data locked to **Internal Storage / YYY**
- Analysis-only crypto multi-timeframe dashboard
- **New neon icon**

## Build APK

1. Upload the source ZIP `TITAN_PRO_v2_1_2.zip` to the **root** of this repository
2. Go to **Actions** → **Build Titan PRO v2.1.2 APK** → **Run workflow**
3. Wait ~15–25 min
4. Download the APK from **Artifacts** or the **Release**

## Install

1. Uninstall any previous Titan app
2. Install the APK
3. Grant **All files access** (Android 11+)
4. Wait 30–90 seconds for the engine to boot
5. Data & logs appear in `/storage/emulated/0/YYY/`

## Source

The original Python source is in `TITAN_PRO_v2_1_2.zip`.  
The workflow unpacks it into `app/src/main/python/` at build time.
