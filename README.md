# Synthara CLI — Downloads

Fertige Fassungen der Synthara-CLI für macOS, Linux und Windows. Dieses Repo enthält nur die Downloads; gebaut werden sie automatisch aus dem Hauptrepo.

## Installieren

**macOS und Linux**

```sh
curl -fsSL https://github.com/Advisori-FTC/syntharacli-releases/releases/latest/download/install.sh | sh
```

**Windows (PowerShell)**

```powershell
irm https://github.com/Advisori-FTC/syntharacli-releases/releases/latest/download/install.ps1 | iex
```

Der Installer lädt das passende Archiv, prüft es gegen `SHA256SUMS` und legt `syntharacli` nach `~/.local/bin` (Windows: `%LOCALAPPDATA%\Programs\syntharacli`).

## Anmelden

```sh
syntharacli login
```

URL und Schlüssel findest du in Synthara unter **Developer**.
