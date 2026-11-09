# Delta Trainer – Installation & Hilfe

**Delta Trainer** ist eine Lern-App für die **DHBW Deltaprüfung** (Studierfähigkeitstest, Testzentrum Heilbronn):
alle sechs Aufgabentypen üben, mit Tipps und Lösungswegen, dazu eine Prüfungssimulation mit geschätzter Punktzahl.
Die App läuft komplett offline auf deinem Mac.

### ⬇️ [Neueste Version herunterladen](https://github.com/shadmehr17/delta-trainer-releases/releases/latest/download/Delta-Trainer-macOS.dmg)

Dieser Link liefert immer die neueste Version (Datei `Delta-Trainer-macOS.dmg`, ca. 5 MB).

*English instructions: [see below](#english).*

---

## Inhalt

1. [Welcher Weg ist für mich?](#welcher-weg-ist-für-mich)
2. [Voraussetzungen prüfen](#1-voraussetzungen-prüfen)
3. [Herunterladen](#2-herunterladen)
4. [Installieren – Weg A: Privater Mac](#weg-a-privater-mac)
5. [Installieren – Weg B: „Delta Trainer ist beschädigt“](#weg-b-wenn-beschädigt-erscheint)
6. [Installieren – Weg C: Firmen-Mac ohne Admin-Rechte](#weg-c-firmen-mac-ohne-admin-rechte)
7. [Updates](#updates)
8. [Deine Daten: Speicherort, Backup, Deinstallieren](#deine-daten)
9. [Häufige Fragen & Probleme](#häufige-fragen--probleme)
10. [English](#english)

---

## Welcher Weg ist für mich?

| Deine Situation | Dein Weg |
|---|---|
| Eigener Mac, du kannst Programme installieren | **[Weg A](#weg-a-privater-mac)** – der normale Weg |
| Beim Öffnen steht **„Delta Trainer ist beschädigt und kann nicht geöffnet werden“** | **[Weg B](#weg-b-wenn-beschädigt-erscheint)** – ein Befehl im Terminal |
| Mac von Firma/Schule, du hast **keine Admin-Rechte** oder es gibt kein „Trotzdem öffnen“ | **[Weg C](#weg-c-firmen-mac-ohne-admin-rechte)** – Installation nur für dich |

Unsicher? Fang mit **Weg A** an. Wenn es dort hakt, verweist die Anleitung auf den nächsten Weg.

---

## 1. Voraussetzungen prüfen

Du brauchst:

- einen **Mac mit Apple-Chip** (M1, M2, M3, M4 … – also ab ca. Ende 2020)
- **macOS 12 Monterey oder neuer**

**So prüfst du beides:**

1. Klicke ganz oben links auf das **Apfel-Symbol** (das Apple-Menü).
2. Wähle **„Über diesen Mac“**.
3. Schau auf die Zeilen:
   - **„Chip“**: Dort muss **„Apple M…“** stehen. Steht dort **„Prozessor … Intel“**, läuft die App leider noch nicht (siehe [FAQ](#ich-habe-einen-intel-mac)).
   - **„macOS“**: Der Name/die Nummer muss **12 (Monterey) oder höher** sein.

<!-- SCREENSHOT 01: images/01-ueber-diesen-mac.png -->
> 📷 *Bild folgt: Fenster „Über diesen Mac“ mit markierten Zeilen „Chip“ und „macOS“.*

---

## 2. Herunterladen

1. Klicke auf **[Neueste Version herunterladen](https://github.com/shadmehr17/delta-trainer-releases/releases/latest/download/Delta-Trainer-macOS.dmg)**.
2. Die Datei **`Delta-Trainer-macOS.dmg`** landet in deinem Ordner **„Downloads“**.

Eine `.dmg`-Datei ist wie ein virtueller USB-Stick: Wenn du sie öffnest, erscheint ein Fenster mit der App darin.

---

## Weg A: Privater Mac

### A1. Installieren

1. Öffne den Ordner **„Downloads“** und doppelklicke auf **`Delta-Trainer-macOS.dmg`**.
2. Es öffnet sich ein Fenster mit dem Delta-Trainer-Symbol links und dem Ordner **„Programme“** rechts.
3. **Ziehe „Delta Trainer“ mit der Maus auf den Ordner „Programme“** (dem Pfeil folgen) und lass los.
4. **Auswerfen:** In der Finder-Seitenleiste neben **„Delta Trainer“** auf das Auswerfen-Symbol ⏏ klicken.
   *(Wichtig: Sonst startest du später versehentlich die App aus der .dmg statt aus „Programme“.)*
5. Die `.dmg`-Datei in „Downloads“ kannst du danach löschen.

<!-- SCREENSHOT 02: images/02-dmg-fenster.png -->
> 📷 *Bild folgt: Installationsfenster mit Pfeil von Delta Trainer zu „Programme“.*

### A2. Erster Start – die macOS-Warnung

Beim ersten Öffnen zeigt macOS eine Warnung, ungefähr so:

> **„Delta Trainer“ wurde nicht geöffnet.** Apple konnte nicht überprüfen, ob „Delta Trainer“ frei von Schadsoftware ist …

**Was bedeutet das?** Apple prüft Apps, deren Entwickler am kostenpflichtigen Apple-Entwicklerprogramm teilnehmen
(das nennt sich *Notarisierung*). Delta Trainer ist ein privates Lernprojekt und (noch) nicht notarisiert.
Die Warnung heißt also **„Apple kennt diese App nicht“** – nicht „diese App ist gefährlich“.
Du entscheidest einmalig, dass du ihr vertraust; danach startet sie ganz normal.

<!-- SCREENSHOT 03: images/03-warnung.png -->
> 📷 *Bild folgt: macOS-Warnung „Delta Trainer wurde nicht geöffnet“.*

**So öffnest du die App trotzdem:**

1. Öffne **„Programme“** und doppelklicke auf **„Delta Trainer“**. Die Warnung erscheint → klicke **„Fertig“**
   (**nicht** „In den Papierkorb legen“).
2. Öffne **Apfel-Symbol oben links → Systemeinstellungen**.
3. Klicke links auf **„Datenschutz & Sicherheit“**.
4. Scrolle rechts **nach unten** bis zum Abschnitt **„Sicherheit“**. Dort steht:
   *„Delta Trainer“ wurde blockiert, um deinen Mac zu schützen.*
5. Klicke daneben auf **„Trotzdem öffnen“**.
6. Bestätige im nächsten Fenster noch einmal mit **„Trotzdem öffnen“** und gib dein **Mac-Passwort** ein
   (oder nutze Touch ID).
7. Delta Trainer startet. 🎉 Ab jetzt öffnest du die App ganz normal per Doppelklick.

<!-- SCREENSHOT 04: images/04-datenschutz-sicherheit.png -->
> 📷 *Bild folgt: Systemeinstellungen → Datenschutz & Sicherheit mit Knopf „Trotzdem öffnen“.*

<!-- SCREENSHOT 05: images/05-bestaetigen.png -->
> 📷 *Bild folgt: Bestätigungsfenster „Trotzdem öffnen“.*

> **Kein Knopf „Trotzdem öffnen“?** Er erscheint nur etwa eine Stunde nach dem Öffnungsversuch – einfach Schritt 1
> wiederholen. Fehlt er auf einem Firmen-Mac ganz, nimm **[Weg C](#weg-c-firmen-mac-ohne-admin-rechte)**.
> Steht statt der Warnung **„ist beschädigt“** da, nimm **[Weg B](#weg-b-wenn-beschädigt-erscheint)**.

---

## Weg B: Wenn „beschädigt“ erscheint

Manchmal meldet macOS: **„Delta Trainer ist beschädigt und kann nicht geöffnet werden. Du solltest es in den Papierkorb legen.“**

**Keine Sorge – die App ist nicht kaputt.** macOS markiert jede Datei aus dem Internet mit einem
*„Aus dem Internet geladen“*-Etikett (Fachwort: *Quarantäne*). Bei nicht notarisierten Apps zeigt macOS dafür
manchmal diese irreführende Meldung. Du entfernst nur dieses Etikett – an der App selbst ändert sich nichts.

1. Installiere die App wie in **[A1](#a1-installieren)** (in „Programme“ ziehen), klicke bei der Meldung auf **„Abbrechen“**.
2. Öffne das **Terminal**: `⌘ + Leertaste` drücken, **Terminal** tippen, `Enter`.
3. Kopiere diese eine Zeile, füge sie im Terminal ein (`⌘ + V`) und drücke `Enter`:

   ```sh
   xattr -dr com.apple.quarantine "/Applications/Delta Trainer.app"
   ```

   *Was der Befehl macht:* `xattr` bearbeitet Datei-Etiketten, `-d` löscht eins (nämlich `com.apple.quarantine`),
   `-r` gilt für alle Dateien in der App. Wenn alles klappt, zeigt das Terminal **nichts** an – das ist richtig so.
4. Öffne Delta Trainer jetzt per Doppelklick. Fertig.

> Steht im Terminal **„Permission denied“**, gehört die App nicht dir (typisch auf Firmen-Macs) → **[Weg C](#weg-c-firmen-mac-ohne-admin-rechte)**.

---

## Weg C: Firmen-Mac ohne Admin-Rechte

Ohne Admin-Rechte darfst du oft nichts in den System-Ordner „Programme“ legen. Du kannst die App aber in deinen
**persönlichen Programme-Ordner** installieren (`~/Applications`, nur für deinen Benutzer).
Dafür braucht es **kein** Admin-Passwort, und **Updates funktionieren dort genauso automatisch.**

> ⚠️ **Firmen-Richtlinien beachten:** Viele Firmen erlauben nur freigegebene Software. Ob du eigene Apps installieren
> darfst, entscheidet deine IT – frag im Zweifel nach, bevor du diesen Weg nutzt.

1. Öffne das **Terminal** (`⌘ + Leertaste` → **Terminal** → `Enter`) und lege den Ordner an (falls er fehlt):

   ```sh
   mkdir -p ~/Applications
   ```

2. Doppelklicke auf **`Delta-Trainer-macOS.dmg`**. Öffne zusätzlich ein Finder-Fenster: **Finder → Gehe zu → Gehe zu Ordner …**
   (`⇧ + ⌘ + G`), tippe `~/Applications` und drücke `Enter`.
   *(Der Ordner heißt im Finder ebenfalls „Programme“, liegt aber in deinem Benutzerordner.)*
3. Ziehe **„Delta Trainer“** aus dem Installationsfenster **in dieses Finder-Fenster** – *nicht* auf den Pfeil-Ordner
   „Programme“ im Installationsfenster (das ist der System-Ordner).
4. Werfe die `.dmg` aus (⏏ in der Finder-Seitenleiste).
5. Entferne im Terminal das Quarantäne-Etikett (Erklärung siehe [Weg B](#weg-b-wenn-beschädigt-erscheint)):

   ```sh
   xattr -dr com.apple.quarantine ~/Applications/"Delta Trainer.app"
   ```

6. Starte die App: im Finder-Fenster `~/Applications` auf **„Delta Trainer“** doppelklicken.
   Tipp: Ziehe sie ins Dock, damit du sie schnell wiederfindest.

---

## Updates

Du musst nichts tun: **Delta Trainer sucht bei jedem Start selbst nach einer neuen Version.**

- Gibt es eine, erscheint oben ein Banner **„Update auf vX.Y.Z verfügbar“** mit einer kurzen Liste der Neuerungen.
- Klicke **„Jetzt installieren“** → die App lädt das Update, installiert es und startet neu. Dein Lernfortschritt bleibt erhalten.
- **„Später“** blendet das Banner aus; beim nächsten Start fragt die App wieder.
- **Während einer Prüfungssimulation** wird nie aktualisiert – das Banner erscheint erst danach.
- Manuell prüfen: unten in der Seitenleiste auf **„Nach Updates suchen“** klicken.

Updates sind digital signiert: Die App installiert nur Pakete, die wirklich vom Delta-Trainer-Entwickler stammen.
Die macOS-Warnung aus Weg A/B kommt bei Updates **nicht** wieder.

<!-- SCREENSHOT 07: images/07-update-banner.png -->
> 📷 *Bild folgt: Update-Banner „Update auf vX.Y.Z verfügbar“ mit Knopf „Jetzt installieren“.*

---

## Deine Daten

<!-- SCREENSHOT 06: images/06-uebersicht.png -->
> 📷 *Bild folgt: Die Übersicht der App nach dem ersten Start.*

### Wo wird mein Fortschritt gespeichert?

Nur auf deinem Mac – nichts geht ins Internet. Alles liegt in diesem Ordner:

```
~/Library/Application Support/de.shadmehr.deltatrainer/
```

(`~` ist dein Benutzerordner. Die Datei `delta.db` enthält alle Antworten und Simulationen.)

### Backup machen

1. **Delta Trainer beenden** (`⌘ + Q`).
2. Im Finder: **Gehe zu → Gehe zu Ordner …** (`⇧ + ⌘ + G`), einfügen:
   `~/Library/Application Support/de.shadmehr.deltatrainer` → `Enter`.
3. Den **ganzen Ordner** kopieren, z. B. auf einen USB-Stick oder in die Cloud.

**Wiederherstellen / neuer Mac:** App installieren, einmal starten und wieder beenden, dann den gesicherten Ordner
an dieselbe Stelle kopieren (vorhandenen ersetzen).

### Komplett deinstallieren

1. Delta Trainer beenden (`⌘ + Q`).
2. Die App in den Papierkorb legen (aus „Programme“ bzw. `~/Applications`).
3. Wenn auch dein Lernfortschritt weg soll, im Terminal:

   ```sh
   rm -rf ~/Library/"Application Support"/de.shadmehr.deltatrainer ~/Library/Caches/de.shadmehr.deltatrainer ~/Library/WebKit/de.shadmehr.deltatrainer
   ```

   ⚠️ Das löscht deinen gesamten Fortschritt endgültig – vorher ein Backup machen, wenn du ihn behalten willst.

---

## Häufige Fragen & Probleme

#### „Delta Trainer ist beschädigt und kann nicht geöffnet werden“
Die App ist nicht kaputt, macOS hat sie nur als „aus dem Internet“ markiert → **[Weg B](#weg-b-wenn-beschädigt-erscheint)**.

#### Es gibt keinen Knopf „Trotzdem öffnen“
Erst die App einmal öffnen (Warnung → „Fertig“), dann innerhalb einer Stunde in die Systemeinstellungen.
Auf Firmen-Macs kann die IT den Knopf abschalten → **[Weg C](#weg-c-firmen-mac-ohne-admin-rechte)**.

#### Ich habe einen Intel-Mac
Die App gibt es derzeit nur für Apple-Chips (M1 und neuer). Eine Version für Intel-Macs ist geplant.

#### Mein macOS ist älter als 12 (Monterey)
Dann startet die App nicht. Prüfe unter **Systemeinstellungen → Allgemein → Softwareupdate**, ob ein Update möglich ist.

#### Das Update-Banner erscheint nie
Die App braucht für die Update-Suche kurz Internet (Verbindung zu `github.com`). Klicke unten in der Seitenleiste auf
**„Nach Updates suchen“**. Steht dort „Keine Verbindung zum Update-Server“, blockiert evtl. ein Firmen-Netzwerk
GitHub – dann die neue Version wie oben herunterladen und einfach über die alte installieren.

#### „Update fehlgeschlagen“
Meist eine unterbrochene Verbindung: App neu starten und noch einmal „Jetzt installieren“ klicken. Hilft das nicht,
die neueste `.dmg` herunterladen und die App ersetzen – dein Fortschritt bleibt erhalten.

#### Geht mein Fortschritt bei einem Update verloren?
Nein. Er liegt getrennt von der App (siehe [Deine Daten](#deine-daten)).

#### Ist die App sicher? Was macht sie mit meinen Daten?
Die App arbeitet offline, speichert nur lokal und kontaktiert das Internet nur, um nach Updates zu suchen (`github.com`).

---

## English

**Delta Trainer** is a study app for the DHBW *Deltaprüfung* (German university aptitude test). The app is in German.

- **Requirements:** Mac with Apple silicon (M1 or newer), macOS 12 Monterey or later
  (check: Apple menu → *About This Mac* → “Chip” and “macOS”).
- **Download:** [latest version](https://github.com/shadmehr17/delta-trainer-releases/releases/latest/download/Delta-Trainer-macOS.dmg) – this link always points to the newest release.
- **Install:** open the `.dmg`, drag *Delta Trainer* onto *Applications*, eject the disk image.
- **First launch:** the app is not notarized by Apple (that requires a paid developer account), so macOS blocks it once.
  Open it, click *Done*, then go to *System Settings → Privacy & Security*, scroll down and click **Open Anyway**,
  confirm with your password.
- **“Delta Trainer is damaged”:** the app is fine; macOS only flagged the download. Run
  `xattr -dr com.apple.quarantine "/Applications/Delta Trainer.app"` in Terminal, then open the app.
- **Managed Mac without admin rights:** create `~/Applications` (`mkdir -p ~/Applications`), drag the app there instead,
  then run `xattr -dr com.apple.quarantine ~/Applications/"Delta Trainer.app"`. Check your company's IT policy first.
- **Updates** are automatic and signed: a banner offers new versions (“Jetzt installieren” = install now). Never during an exam simulation.
- **Your data** stays on your Mac in `~/Library/Application Support/de.shadmehr.deltatrainer/`. Back it up by copying
  that folder while the app is closed. To uninstall, delete the app and that folder (plus `~/Library/Caches/…` and
  `~/Library/WebKit/de.shadmehr.deltatrainer`).

---

*Dieses Repo enthält nur Release-Dateien (Installer, signierte Update-Pakete, `latest.json`), keinen Quellcode.*
