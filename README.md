# WAG Trust Panel

A small desktop utility that gives clear, human-readable visibility into what a Windows laptop is actually doing.

This tool reduces uncertainty by replacing guesswork with observable system facts. It shows running processes, active network connections, and performs a simple preflight health check so a user can quickly see whether their machine is behaving normally.

This tool is intentionally simple, transparent, and non-invasive.

---

## Installation (on the target laptop)

git clone https://github.com/Kamanaka5502/wag_trust_pane

cd wag_trust_panel

pip install -r requirements.txt

python main.py

---

## File Structure


File Structure

wag_trust_panel/
main.py
ui.py
system_monitor.py
preflight_check.py
requirements.txt

## Design Philosophy

This project applies simple observability principles to personal computing:

Show real system state

Remove mystery

Provide reassurance through facts

Keep the tool transparent and understandable

## Future Additions

Gmail inbox noise filtering

Startup program viewer

Expanded system checks

Logging for historical comparison
