<p align="center">
  <img src="docs/icon.png" width="96" alt="AI Agent">
</p>

<h1 align="center">AI Agent by agenturWEHRLI</h1>

<p align="center">
  <strong>Dein persönlicher KI-Assistent für den Desktop – zum Sprechen, mit Gedächtnis, Kalender und Mail.</strong><br><br>
  macOS · Windows · Linux &nbsp;|&nbsp; kostenlos
</p>

<p align="center">
  <a href="https://github.com/danielwehrli/ai-agent-releases/releases/latest"><strong>⬇ Neueste Version herunterladen</strong></a>
</p>

---

### Was ist AI Agent?

Ein Assistent wie JARVIS auf deinem Computer: Du sprichst ihn mit seinem Namen an («Hey Max, was steht heute an?») und er antwortet mit Stimme – kurz und hilfreich. Ausführliches wie Rezepte, Mail-Entwürfe oder Rechercheergebnisse zeigt er dir als Karte am Bildschirm.

- **Mehrere Agenten** – z. B. Max (witzig) und Simon (sarkastisch). Jeder mit eigenem Namen, eigener Farbe, eigenem KI-Modell und eigener Stimme. Der Name ist das Wake-Word.
- **Denkt mit** – kennt deine Termine, Aufgaben, Mails und die Personen in deinem Haushalt. Kommen laut Kalender Gäste, rechnet er das Rezept gleich für alle.
- **Gedächtnis** – merkt sich Vorlieben, Allergien, Geburtstage usw. pro Person. Alles einsehbar und löschbar.
- **Google Kalender & Gmail** – Termine lesen und eintragen, wichtige Mails erkennen, Antworten vorbereiten. Gesendet wird nur nach deiner Bestätigung.
- **Kochmodus** – Rezepte Schritt für Schritt, gesteuert mit «weiter», «zurück», «nochmal» – mit Timern.
- **Erinnerungen & Aufträge im Hintergrund** – «Erinnere mich morgen um 9», «Recherchier mir drei Hotels im Tessin und melde dich».
- **Morgen-Briefing**, Websuche, Bilder erzeugen
- **Stimmen** – lokal und gratis (Piper), Systemstimme oder ElevenLabs inkl. eigener geklonter Stimme
- **Datenschutz** – Gedächtnis, Verlauf und Zugangsdaten bleiben lokal auf deinem Computer
- Automatische Updates

### Download

| System | Datei |
|---|---|
| **macOS** (Apple Silicon & Intel) | `AI.Agent.by.agenturWEHRLI_x.y.z_universal.dmg` |
| **Windows** 10/11 | `AI.Agent.by.agenturWEHRLI_x.y.z_x64-setup.exe` (oder `.msi`) |
| **Linux** | `.AppImage`, `.deb` oder `.rpm` |

👉 **[Zur neuesten Version](https://github.com/danielwehrli/ai-agent-releases/releases/latest)**. Die Dateien findest du dort unter **«Assets»**.
Die Dateien mit der Endung `.sig` und `latest.json` sind für die automatischen Updates und müssen nicht heruntergeladen werden.

### Installation

**macOS**
1. Die `.dmg` öffnen und **AI Agent by agenturWEHRLI** in den Ordner **Programme** ziehen.
2. Beim ersten Start meldet macOS eventuell, dass die App aus dem Internet stammt. Öffne dann **Systemeinstellungen → Datenschutz & Sicherheit**, scrolle nach unten und klicke auf **«Trotzdem öffnen»**.
3. Falls die Meldung «ist beschädigt» erscheint, im Terminal einmalig ausführen:
   ```
   xattr -cr "/Applications/AI Agent by agenturWEHRLI.app"
   ```
4. Beim ersten Zuhören fragt macOS nach dem Mikrofon – bitte erlauben.

**Windows**
1. Die `-setup.exe` starten.
2. Falls «Der Computer wurde durch Windows geschützt» erscheint: **Weitere Informationen → Trotzdem ausführen**.

**Linux**
- `.AppImage`: ausführbar machen (`chmod +x`) und starten, oder
- `.deb` / `.rpm` mit dem Paketmanager installieren.

### Los geht's

1. Erstelle ein kostenloses Konto auf [console.groq.com](https://console.groq.com) und erstelle unter **API Keys** einen Schlüssel.
2. Öffne AI Agent → **Einstellungen → Allgemein** → Groq-Key einfügen → **Speichern**. Die deutsche Stimme wird beim ersten Start automatisch geladen (ca. 60 MB).
3. Optional: **Einstellungen → Google → «Mit Google verbinden»** für Kalender und Gmail. Erscheint «Diese App wurde nicht von Google überprüft», auf **Erweitert → Weiter zu AI Agent** klicken.
4. Unter **Personen** deinen Haushalt erfassen, unter **Agenten** Namen, Persönlichkeit und Stimme wählen.
5. **Ctrl + Shift + Leertaste** (Mac: **⌘ + Shift + Leertaste**) drücken oder auf die Kugel klicken – und lossprechen. ✨

Im Modus **«Immer – auf Namen reagieren»** genügt ein «Hey Max …» ohne Taste.

### Ideen zum Ausprobieren

- «Hey Max, was steht heute an?»
- «Max, such mir ein Rezept für Kürbissuppe – wir sind am Freitag zu siebt.» → dann «Schritt für Schritt»
- «Erinner mich in 20 Minuten an den Ofen.»
- «Max, hab ich wichtige Mails?» – «Simon, was hältst du vom Entwurf?»
- «Trag mir Dienstag 14 Uhr Zahnarzt ein.»
- «Merk dir: Lena isst keine Pilze.»

### Kosten

Die App ist **kostenlos**. Groq bietet einen Gratis-Zugang mit Limits, der für den persönlichen Alltag meist reicht. Optionale Dienste (Replicate, ElevenLabs) rechnen direkt mit dir ab.

Gefällt dir AI Agent? ☕ **[Kaffee spendieren](https://revolut.me/danwehrli)** – danke!

### Datenschutz & Bedingungen

- [Datenschutzerklärung](https://agenturwehrli.ch/ai-agent-datenschutz)
- [Nutzungsbedingungen](https://agenturwehrli.ch/ai-agent-nutzungsbedingungen)

---

<p align="center">
  AI Agent by agenturWEHRLI · Daniel Wehrli | <a href="https://agenturwehrli.ch">agenturwehrli.ch</a>
</p>
