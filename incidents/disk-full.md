# Incident: Disk Full on Root Filesystem

## Baseline
Initial disk state before the incident.
![Baseline](screenshots/disk-full/01-baseline.PNG)

## Incident Detection
Root filesystem usage reached a critical level.
![Disk full](screenshots/disk-full/02-disk-full.PNG)

## Investigation
Disk usage investigation identified the root cause.
![Root cause](screenshots/disk-full/03-root-cause.PNG)

## Resolution
Unnecessary files were removed and disk space was freed.
![After fix](screenshots/disk-full/04-after-fix.PNG)

## Lessons Learned
- Disk usage should be monitored continuously
- Temporary directories can quickly consume disk space
- Root filesystem requires special attention
