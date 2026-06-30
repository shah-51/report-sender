# Report Sender

### 👉 [**Download it here**](https://shah-51.github.io/report-sender/) — one click, picks the right file for your computer.

A small desktop app that captures a range from a Google Sheet as an image and posts it to a
WhatsApp group — on demand or on a daily / weekly / monthly schedule. Runs entirely on your own
computer. No server, no paid services.

## Download & install

Grab the latest from the [**Releases**](../../releases/latest) page:

| Your computer | File |
|---|---|
| **Windows** | `Report-Sender-Setup-x.y.z.exe` |
| **Mac (Apple Silicon · M1/M2/M3/M4)** | `Report-Sender-x.y.z-arm64.dmg` |
| **Mac (Intel)** | `Report-Sender-x.y.z.dmg` (the one without `arm64`) |

**Windows:** run the installer. Windows may warn "unknown publisher" → **More info → Run anyway**
(the app isn't code-signed). It installs to the Start menu and a desktop shortcut.

**Mac:** open the `.dmg`, drag **Report Sender** to Applications. First launch: **right-click the
app → Open** (macOS Gatekeeper blocks unsigned apps on a normal double-click).

The app **auto-updates** itself (Windows & Apple-Silicon Mac) from this page. Intel Mac: re-download
when a new version ships.

## First-time setup (about 5 minutes)
1. **Connect Google** — log into the account that can see your sheet, then click "I've logged in".
2. **Connect WhatsApp** — scan the QR with your phone (WhatsApp → Linked devices).
3. **+ Add report** — paste the Google Sheet URL, the range (e.g. `B64:C90`), and the exact
   WhatsApp group name. **Send now** to test.
4. **🕒 Schedule** on the report card to set frequency, time(s), and time zone.

Closing the window keeps it running in the system tray so schedules fire. Enable "Start
automatically at login" so it's always ready.

## Privacy
There is **no server**. Nothing is sent to the developer or any third party. Your WhatsApp
session, Google login, settings, and the report image all stay in a local folder on your own
computer. The only network traffic is to **your** Google account (to fetch your sheet) and **your**
WhatsApp (to post to your group). You can remove the WhatsApp linked device and sign out Google at
any time.
