# Scoop bucket for Vallaury

[Vallaury](https://vallaury.it) for Windows, installed with [Scoop](https://scoop.sh).

```powershell
scoop bucket add vallaury https://github.com/Vallaury/scoop-vallaury
scoop install vallaury
```

Update with `scoop update vallaury`. Uninstall with `scoop uninstall vallaury`.

The package installs the official installer from the
[GitHub releases](https://github.com/Vallaury/vallaury-desktop/releases)
of the app, after checking its SHA-256. The installer is not code-signed yet,
so Windows SmartScreen may ask for confirmation.

The app source is at https://github.com/Vallaury/vallaury-desktop (GPL-3.0-only).
