<div align="center">

# Report Sender

**Send a Google Sheet report to a WhatsApp group, automatically.**

On demand, or on a daily, weekly, or monthly schedule. Runs on your own computer. No server, no cost.

<br>

<a href="https://github.com/shah-51/report-sender/releases/latest">
  <img src="https://img.shields.io/badge/Download%20Report%20Sender-4f46e5?style=for-the-badge&logo=github&logoColor=white" height="46" alt="Download Report Sender">
</a>

<br><br>

Free. Works on Windows and macOS.

</div>

---

## Which file do I download?

After clicking **Download Report Sender** above, pick the file for your computer:

| Your computer | File to download |
|---|---|
| **Windows** | `Report-Sender-Setup-x.y.z.exe` |
| **Mac (Apple Silicon: M1, M2, M3, M4)** | `Report-Sender-x.y.z-arm64.dmg` |
| **Mac (Intel)** | `Report-Sender-x.y.z.dmg` (the one without `arm64`) |

**Windows.** Run the installer. Windows may warn "unknown publisher"; click **More info**, then **Run anyway**. The app is safe, it just is not code signed yet. It installs to the Start menu and adds a desktop shortcut.

**Mac.** Open the `.dmg` and drag **Report Sender** into Applications. The first time you open it, **right click the app and choose Open** (macOS blocks unsigned apps on a normal double click).

The app updates itself when a new version ships, so you only download once.

## Set it up (about 5 minutes)

1. **Install and open** Report Sender.
2. **Connect Google.** Log into the account that can see your sheet, then click "I've logged in".
3. **Connect WhatsApp.** Scan the QR code with your phone (open WhatsApp, go to Linked devices).
4. **Add a report.** Paste your Google Sheet URL, the cell range (for example `B64:C90`), and the exact WhatsApp group name. Click **Send now** to test it.
5. **Schedule it.** On the report card, click the clock to set how often, what time, and your time zone.

Closing the window keeps the app running in the system tray so schedules still fire. Turn on "Start automatically at login" so it is always ready.

## Is it private?

Yes. There is no server, so nothing is sent to the developer or any third party. Your WhatsApp session, Google login, settings, and the report image all stay in a folder on your own computer. The only network traffic goes to your own Google account (to read your sheet) and your own WhatsApp (to post to your group). You can disconnect either one at any time.
