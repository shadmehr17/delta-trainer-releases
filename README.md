# Delta Trainer – Releases

Downloads für **Delta Trainer**, eine Lern-App für die DHBW Deltaprüfung (macOS, Apple Silicon).

➡️ **[Neueste Version herunterladen](https://github.com/shadmehr17/delta-trainer-releases/releases/latest)** – Datei `Delta-Trainer_…_aarch64.dmg`

## Installieren
1. `.dmg` öffnen und „Delta Trainer“ in den Ordner „Programme“ ziehen.
2. Die App ist nicht von Apple signiert. Beim ersten Start blockiert macOS sie:
   **Systemeinstellungen → Datenschutz & Sicherheit → „Trotzdem öffnen“**.
3. Danach sucht die App selbst nach Updates und installiert sie auf Knopfdruck.

## Was hier liegt
Dieses Repo enthält nur Release-Dateien, keinen Quellcode:
- `*.dmg` – Installer
- `*.app.tar.gz` + `.sig` – signiertes Update-Paket für die Auto-Update-Funktion
- `latest.json` – wird von der App abgefragt, um neue Versionen zu finden
