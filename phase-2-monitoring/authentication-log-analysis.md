# Authentication Log Analysis (Phase 2)

## Objective
To practice SOC-style monitoring and investigation by reviewing Linux authentication logs and identifying successful and failed SSH login attempts.

---

## Log Source
- **System:** Raspberry Pi 4 (“Gojo”)
- **Logging Method:** systemd journal
- **Service:** sshd

Logs were accessed using:
```bash
journalctl -u ssh
