# MyRDP

Private GitHub Actions Windows RDP workflow.

Required repository secrets:

- TS_AUTHKEY
- RDP_PASSWORD
- BACKUP_PASSWORD

Run either workflow from the Actions tab:

- Secure temporary Windows RDP (A)
- Secure temporary Windows RDP (B)

It restores the latest encrypted backup from the rdp-backups branch, saves a startup backup, auto-saves every 15 minutes, and saves a final backup before shutdown.
