# omarchy-cmd-screensaver

Replaces Omarchy's default screensaver to keep TTE animations synchronized across multiple monitors.

## Install

```bash
# Backup default script (idempotent: does not overwrite existing backup)
cp -n "$(which omarchy-cmd-screensaver 2>/dev/null)" ./omarchy-cmd-screensaver.bak 2>/dev/null || true

# Install custom script
cp omarchy-cmd-screensaver $(which omarchy-cmd-screensaver)
```
