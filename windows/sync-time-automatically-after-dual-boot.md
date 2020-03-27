# Sync time automatically after dual boot

When dual booting Windows with another OS, when booting Windows after booting the another OS, windows time gets unsyncronized.

To fix the issue, one can:
1. Go to the Services window (search "Services")
2. Find service "Windows Time"(w32time)
3. Change "Startup Type" from Manual to Automatic.

### Source
https://stackoverflow.com/a/55128248
