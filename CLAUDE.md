# Vault Context

Dieses Vault ist das Zweites Gehirn von Arian.

## Über mich

Arian, Student der Maschinenbau an der Hochschule Pforzheim ab Wintersemester 2026. Strukturiert, sorgfältig und offen in der Kommunikation – spricht Sachen knallhart und direkt an. Momentan in intensiver Vorbereitung auf das Studium und baut parallel sein KI-Wissen zu Maximum auf. Ausführliches Profil in [[00 Kontext/Über mich]].

## Vault-Struktur

- **00 Kontext/**: Persönliches Kontext-Profil (Über mich, ICP, Angebot, Schreibstil, Branding). Zentrale Referenz für alle inhaltlichen Aufgaben.
- **01 Inbox/**: Schnelle Gedanken, Brain Dumps, unverarbeitete Notizen. Alles was noch keinen festen Platz hat landet hier.
- **02 Projekte/**: Aktive Projekte mit konkretem Ziel und Enddatum. Startet als einzelne .md Datei.
- **03 Bereiche/**: Laufende Verantwortungsbereiche ohne Enddatum (Studium, KI Wissen, Finanzen). Jeder Bereich ist ein Ordner, weil Bereiche über die Zeit wachsen.
- **04 Ressourcen/**: Referenzmaterial, Wissen, gesammelte Informationen (KI Tools und Anwendungen).
- **05 Daily Notes/**: Tägliches Logbuch. Was an einem Tag passiert, welche Entscheidungen getroffen wurden, was offen ist.
- **06 Archiv/**: Abgeschlossene Projekte und inaktive Bereiche. Aus dem aktiven Blickfeld, aber durchsuchbar.
- **07 Anhänge/**: Bilder, PDFs, Medien. Obsidian legt hier automatisch alle eingefügten Dateien ab.

## Regeln für dieses Vault

- Nutze [[Wikilinks]] für Verknüpfungen zwischen Notizen
- Neue Notizen ohne klaren Platz kommen in 01 Inbox/
- Halte Notizen atomar: eine Idee pro Notiz wo möglich. Ausnahme: Daily Notes fassen einen ganzen Tag zusammen.
- Daily Notes benennen im Format: YYYY-MM-DD.md (z.B. 2026-07-26.md). So sortieren sie automatisch chronologisch.
- Nutze YAML Frontmatter: tags, status (aktiv/abgeschlossen/pausiert), date
- Dateinamen in normaler Schreibweise mit Leerzeichen und Großbuchstaben: Beschreibender Name.md
- Neue Projekte bekommen eine einzelne .md Datei direkt unter 02 Projekte/. Unterordner nur wenn das Projekt mehrere Dateien braucht.
- Bereiche und Ressourcen sind immer Ordner, weil sie über die Zeit wachsen
- Abgeschlossene Projekte nach 06 Archiv/ verschieben. Nur auf Anweisung, nicht eigenständig.
- Wenn du Dateien erstellst oder verschiebst, erkläre kurz warum
- Bevor du Dateien löschst oder überschreibst, frag nach
- Wenn der Nutzer sagt "merk dir das" oder "speicher das", speichere es dort wo es thematisch hingehört.

## Session-Routinen

### Bei Session-Start
1. Prüfe 01 Inbox/ auf neue Notizen, zeige was drin liegt, und biete an die Einträge einzusortieren

### Kontext bei Bedarf
Wenn der Nutzer fragt "Was ist gerade aktuell?" oder "Wo war ich stehen geblieben?": Lies die letzten 2-3 Daily Notes in 05 Daily Notes/ und aktive Projekt-Dateien in 02 Projekte/ um ein Briefing zu geben.

### Bei Session-Ende
Biete an:
1. Einen Daily Note Eintrag in 05 Daily Notes/ zu erstellen mit einer Zusammenfassung des Tages
2. Neue Erkenntnisse als Notizen zu speichern
3. Die Inbox aufzuräumen falls nötig

### Wöchentliche Routinen

**Jeden Sonntag zum Wochenende**:
1. Alle Daily Notes der Woche zusammenfassen (übersichtlich, nicht komplett)
2. Als `KW{Nummer}-{Jahr}.md` (z.B. KW30-2026.md) in 06 Archiv/ speichern
3. Original Daily Notes der Woche aus 05 Daily Notes/ löschen
4. Format: Gesamt-Zusammenfassung der Woche (keine Tag-für-Tag-Auflistung)
