# WAG Trust Panel

A small desktop utility that gives clear, human-readable visibility into what a Windows laptop is actually doing.

WAG Trust Panel reduces uncertainty by replacing guesswork with observable system facts. It shows running processes, active network connections, and performs a simple **preflight health check** so a user can quickly see whether their machine is behaving normally.

This tool is intentionally simple, transparent, and non-invasive.

---

## Purpose

Many people feel uneasy about their computers because system activity is invisible and hard to interpret. This tool provides a plain dashboard that answers:

- What programs are running?
- What network connections are active?
- Does the system look healthy right now?

It does **not** monitor, spy, or collect data. It only displays information already available on the local machine.

---

## Features

### System Activity
- Lists active processes
- Shows outbound network connections
- Displays real, current system state

### Preflight Check
- Quick system health check
- Flags unusual CPU or connection patterns
- Returns a simple **"System looks normal"** when everything is fine

### Simple UI
- Built with Tkinter
- One window, three buttons, immediate feedback
- Designed for non-technical users

---

## Requirements

- Windows laptop
- Python 3.10+
- Internet connection (only for installing packages)

You’re one tiny Markdown rule away from perfect.

Code blocks.

Anything that is a command, file tree, or package list must be inside triple backticks. Without them, GitHub renders it as plain text and it looks “off”.

Replace just these sections.

Replace Python packages used with:
### Python packages used



psutil
requests
google-api-python-client
google-auth-httplib2
google-auth-oauthlib
---

## Installation (on the target laptop)

Clone the repository:

git clone https://github.com/Kamanaka5502/wag_trust_panel
cd wag_trust_panel


Install dependencies:

pip install -r requirements.txt


Install dependencies:

pip install -r requirements.txt

---

## File Structure

wag_trust_panel/
├─ main.py
├─ ui.py
├─ system_monitor.py
├─ preflight_check.py
└─ requirements.txt


---

## Design Philosophy

This project applies simple observability principles to personal computing:

- Show real system state
- Remove mystery
- Provide reassurance through facts
- Keep the tool transparent and understandable

---

## Future Additions

- Gmail inbox noise filtering
- Startup program viewer
- Expanded system checks
- Logging for historical comparison


