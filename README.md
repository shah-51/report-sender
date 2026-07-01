<div align="center">

# Report Sender

**Send a Google Sheet report to a WhatsApp group, automatically.**

On demand, or on a daily, weekly, or monthly schedule. Runs on your own computer. No server, no cost.

<br>

<a href="https://github.com/shah-51/report-sender/releases/latest/download/Report-Sender-Setup.exe"><img src="https://img.shields.io/badge/Download%20for%20Windows-4f46e5?style=for-the-badge&logo=windows&logoColor=white" height="46" alt="Download for Windows"></a>
&nbsp;&nbsp;
<a href="https://github.com/shah-51/report-sender/releases/latest/download/Report-Sender-arm64.dmg"><img src="https://img.shields.io/badge/Download%20for%20Mac-4f46e5?style=for-the-badge&logo=apple&logoColor=white" height="46" alt="Download for Mac"></a>

<br><br>

Click your button and the installer downloads right away. Free.

</div>

---

## Install

**Windows.** Run the downloaded `Report-Sender-Setup.exe`. Windows may warn "unknown publisher"; click **More info**, then **Run anyway**. The app is safe, it just is not code signed yet. It installs to the Start menu and adds a desktop shortcut.

**Mac (Apple Silicon: M1, M2, M3, M4).** Open the downloaded `.dmg` and drag **Report Sender** into Applications. The first time you open it, **right click the app and choose Open** (macOS blocks unsigned apps on a normal double click). Intel Macs are not supported yet.

The app updates itself: when a new version is out, a banner appears at the top with a **Restart to update** button. You only download by hand this one time.

## Set it up (about 5 minutes)

1. **Install and open** Report Sender.
2. **Connect Google.** Log into the account that can see your sheet, then click "I've logged in".
3. **Connect WhatsApp.** Scan the QR code with your phone (open WhatsApp, go to Linked devices).
4. **Add a report.** Paste your Google Sheet URL, the cell range (for example `B64:C90`), and the exact WhatsApp group name. Click **Send now** to test it.
5. **Schedule it.** On the report card, click the clock to set how often, what time(s), and your time zone. You can send several times a day, on chosen weekdays, or on chosen dates of the month.

Closing the window keeps the app running in the system tray so schedules still fire. Turn on "Start automatically at login" so it is always ready.

## Is it private?

Yes. There is no server, so nothing is sent to the developer or any third party. Your WhatsApp session, Google login, settings, and the report image all stay in a folder on your own computer. The only network traffic goes to your own Google account (to read your sheet) and your own WhatsApp (to post to your group). You can disconnect either one at any time.
