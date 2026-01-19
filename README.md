# WashDog 🐶 – Personal Session Guard (Python)

WashDog is a small security tool that helps you monitor **who is using your own computer**.

The first version focuses on a simple scenario:  
if someone uses your machine and it is **not you**, WashDog will:

- capture a picture of the person using the device (via webcam),
- record a summary of the session activity (e.g., active windows, timestamps),
- send you an email notification with the captured evidence.

The goal of this project is educational and defensive:  
to protect your **own devices** in case of theft or unauthorized access, **not** to spy on others.

---

## Features (v1 – in progress)

- 🔍 Basic “non-owner” session detection.
- 📸 Webcam capture of the current user.
- 📝 Local session logging (what happens during the suspicious session).
- 📧 Email notification with attached picture and log file.

---

## Future Ideas

- Per-OS integrations (Windows / macOS / Linux) with dedicated system APIs.
- Encrypted storage of evidence.
- Web dashboard to browse past security events.
- Multi-device support.

---

## Tech Stack

- Language: **Python 3**
- OS-specific modules: separate implementations for **Windows** and **macOS**
- Notifications: **SMTP email** (configurable)

> ⚠️ **Legal & ethical note:**  
> Use WashDog **only on devices that you own or administer** and always respect local laws and privacy rules.
