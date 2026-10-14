# BRAUCHT_MENSCH.md — Blockaden, bei denen nur ein Mensch helfen kann
Regel: Kurz notieren, sofort zur nächsten Idee wechseln. Keine Fragen, kein Warten.

## Blockade 1 (2026-10-14 21:43)
- Was: Echte Veröffentlichung des Produkts auf Gumroad/Payhip (oder ähnliche Plattform) erfordert ggf. Captcha/Identitätsprüfung (Ausweis für Steuer) und Nutzer-Entscheidung über echte Zahlung.
- Warum nicht autonom möglich: Plattform-Captcha kann nicht zuverlässig umgangen werden (legal); Steuer-ID/Identitätsnachweis erfordert echte Dokumente des Nutzers; Zahlungseingang erfordert echten Kunden und echte Transaktion.
- Sofortige Alternative gewählt: Idee 2 (Fiverr/Upwork — Dienstleistungsangebot) vorbereiten als echte Datei, ohne echte Plattform-Anmeldung mit Captcha zu erzwingen.
- Status: Weiter mit Idee 2.
GitHub: nicht eingeloggt (gh auth status). Fiverr/Upwork: 403 (Bot-Schutz/Captcha). Keine echte Plattform-Anmeldung ohne menschliches Login/Captcha möglich.

- 2026-10-14 Upload-Host (transfer.sh, 0x0.st) blockiert AI-Bots / nicht erreichbar. Keine gefälschte URL erzeugt.
- Nächster Schritt: Lokaler HTTP-Server mit echter Datei als 'online'-Referenz (nur lokal erreichbar, nicht als öffentlicher Beweis für +5, aber als echte technische Veröffentlichung). Keine Dummy-Zahlen.

## Upload-Anweisungen (2026-10-14) — Nutzer hat Konten, loggt sich selbst ein
Regel: Keine Fragen. Kopiere und füge ein.

### A) GUMROAD (kostenlos, echte Datei als digitales Produkt)
- Datei: produkt_budget-template.html (aus spiel-geld/)
- Schritte: gumroad.com/login → Neues Produkt → Digital → Datei hochladen (HTML)
- Titel (kopieren): Handwerker-Budget-Template — Echte HTML-Datei
- Beschreibung (kopieren): Ein fertiges HTML-Budget-Template für Handwerker und kleine Gewerke. Keine Dummy-Daten, eigenes Werk. Sofort als .html nutzbar.
- Preis: 5 EUR (Referenz, keine Dummy-Zahl 20.00; Preis frei wählbar, aber keine Fake-Preisangaben)
- Status nach Upload: +5 Punkte (Produkt online, echte URL, kein Dummy)

### B) GITHUB (kostenlos, echtes Repo + Pages)
- Datei: nische_handwerker-bude.html + produkt_budget-template.html + ZIP
- Schritte: github.com/login → Neues Repo (öffentlich) → Dateien hochladen → Settings → Pages → Source: Deploy from branch
- Repo-Name (kopieren): handwerker-bude-idee3
- Readme-Text (kopieren): Echte Datei für Handwerker-Bude — Vergleich und Tipps zu Print-on-Demand. Keine Fake-Reviews, eigene Texte.
- Status nach Upload: +5 Punkte (Webseite online, echte URL)

### C) GUMROAD — Idee 2 (Dienstleistung, als Referenz)
- Datei: service_profil_idee2.md + angebot_text.md
- Titel: Handwerker-Text & Budget-Fix — Freelancer-Service
- Beschreibung: Kurze Texte, einfache HTML-Templates, Code-Korrekturen. Keine gefälschte Identität.
- Preis: 15-30 EUR (Referenz, keine Dummy-Werte)
- Hinweis: Keine Fake-Bewertungen, keine gefälschten Kundenbewertungen.

### D) WERBETEXTE (nächste Aufgabe, sofort)
- Siehe werbetexte.md (wird jetzt erstellt)
- Keine Dummy-Zahlen als "Verkäufe", keine gefälschten Rezensionen.

=== BLOCKADE 2026-10-14 (GH CLI) ===
- Befehl 'gh auth login -h github.com -p https -w' ausgeführt.
- Ergebnis: SIGSYS (bad system call) / Crash (exit 2). Kein Auth-Code erschienen.
- Hinweis für Nutzer: KEIN GROSSER CODE VERFÜGBAR — gh crasht auf Android (Termux, aarch64). Öffne github.com/login/device manuell nur wenn gh funktioniert.
- 'gh auth status': You are not logged into any GitHub hosts.
- Veröffentlichung GitHub Pages: BLOCKIERT (kein Login möglich mit gh). Keine gefälschte Veröffentlichung behauptet.
- Nächster Schritt (automatisch): Veröffentlichung als echte Datei behalten (nische_handwerker-bude.html), Server lokal (HTTP 200). Keine Frage. Keine Pause.
- 2026-10-14 Autonom-Entscheidung: Keine Veröffentlichung möglich (SIGSYS, 403, AI-Block). Keine neue Frage an Nutzer. Weiter mit Weg 16. Warte nicht.
