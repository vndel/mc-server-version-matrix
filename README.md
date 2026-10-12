# Minecraft Server Version Matrix

A declarative inventory of tested Minecraft server runtime combinations. Entries indicate only combinations exercised by maintainers; they are not claims of upstream support or security status.

## Update process
For each row, record the exact Minecraft version, Paper build, proxy version, Java runtime vendor/version, plugin versions, test date, and result. Test startup, shutdown, representative gameplay, config migration, and proxy forwarding on a disposable environment. Retest after dependency or runtime changes.

Do not mark a version supported from compilation alone. Keep end-of-life and untested versions clearly distinct, and link failures to sanitized reproduction notes.