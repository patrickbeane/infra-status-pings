## Real-Time Infrastructure Notifications to Discord

While these integrations are well-documented individually, this repo shows how to unify them—turning backup failures, uptime blips, and firewall bans into a single, coherent signal loop for live infrastructure resilience.

Production services don’t operate in silence. Borgmatic, HetrixTools, and CrowdSec all speak through Discord webhook alerts—giving my infrastructure a voice when it matters most.

### Files
- configs/crowdsec-discord.yaml (redacted sensitive info)
- configs/borgmatic-discord.yaml (redacted sensitive info)
- configs/hetrixtools-discord.png (redacted sensitive info)
- README.md (this file)

### Alert Examples (Screenshots)
- screenshots/crowdsec.png
- screenshots/borgmatic.png
- screenshots/hetrixtools.png

### What It Covers
- Backup success/failure (Borgmatic)
- Uptime monitoring (HetrixTools)
- Firewall bans (CrowdSec)

### Visual Examples
- CrowdSec → Discord channel for banned IP alerts
- Borgmatic → Backup status updates (success/fail/start)
- HetrixTools → Uptime monitoring notifications

### Philosophy
No custom scripts. Just good tools, smart defaults, and clear signals.
This setup favors simplicity and resilience—less to break, easier to trust.