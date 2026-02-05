# Phase 1 Evidence – Commands Used

## SSH / Auth
- sudo journalctl -u ssh --since "1 hour ago"
- sudo journalctl -u ssh
- sudo journalctl | grep sudo

## Time Sync / NTP (Pi-hole layer)
- sudo grep -i ntp /var/log/pihole/FTL.log
- sudo grep -i time /var/log/pihole/FTL.log || echo "No matches found"
