# IZANAGI - V01

Hey, welcome to my passion project. This is a proof of concept pentest toolkit that I threw together.
PLEASE dont be a fucking asshole with it, use it like a normal person would.

## What's Inside

- Port Scanner (TCP connect)
- Service Banner Grabbing
- SSH Connection Check
- CVE Database Lookup
- MYRIAD TRUTHS cleanup
- Some hidden shit you'll have to find

## Setup

You'll need:
- Python 3.8+
- PowerShell
- `colorama` (optional but makes it look better)

Run this shit:
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Running It

```powershell
python main.py
```

## How to Use

1. Pick options by typing numbers (1-9)
2. Follow the yellow prompts
3. After each command you can clear the screen or keep going
4. For the nmap stuff, you need `nmap` installed or it'll try python-nmap instead

## Notes about Features

**Nmap Integration**
- Uses system nmap if you got it
- Falls back to python-nmap if not
- Pretty straightforward

**CVE Lookup**
- Needs an API key for better rate limits
- Saves results in the tmp folder

**Scan Reports**
- JSON (full details)
- CSV (basic shit)
- Auto-saves your last scan

Remember to only scan shit you're allowed to, I'm not responsible for your dumbass decisions lmao

with love,

bell <3

---
btw this was fixed using alot of cursor shit. some notes might not fully explain what i was going for.
