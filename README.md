# Avello Labs downloads

This repository only hosts downloads for Avello Labs apps. Avello Tech Logs
reads them from here to update itself:

- `latest.json`: the newest version, where to download it and its SHA-256,
  signed with Avello Labs' update key; the app takes nothing that isn't
  signed by that key, and installs only when the office says yes
- `AvelloTechLogs-Setup-<version>.exe`: installers
- `offices/*.pack`: each customer's settings, encrypted with a code only that
  customer and Avello Labs have

Nothing here is readable customer data. Please don't open issues or pull
requests; contact harris@avellolabs.com.
