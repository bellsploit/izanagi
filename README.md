# IZANAGI - V01

Hey, welcome to my passion project. This is a proof of concept pentest toolkit that I threw together.

## What's Inside

- Port Scanner (TCP connect)
- Service Banner Grabbing
- SSH Connection Check
- CVE Database Lookup

## Setup

You'll need:
- Python 3.8+
- PowerShell
- `colorama` (optional but makes it look better)

dependencies
```powershell
pip install -r requirements.txt
```

## Running it

```powershell
python main.py
```

alternatively, if you installed a release you can use the executable (after you install dependancies, i think?)

## How to Use

1. Pick options by typing numbers (1-9)
2. Follow the yellow prompts
3. After each command you can clear the screen or keep going
4. For the nmap stuff, you need `nmap` installed or it'll try python-nmap instead

Remember to only scan shit you're allowed to, I'm not responsible for your dumbass decisions lmao

with love,

bell <3

---
btw this was fixed using alot of cursor shit. some notes might not fully explain what i was going for.
