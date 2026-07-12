---
name: spiel-planung
description: Verwaltet Spielideen und Aufgaben für das aktuelle Spiel
---

# Spielplanung

## Wichtig
- Alle Ideen und Aufgaben beziehen sich NUR auf das aktuelle Spiel
- Es gibt kein "nächstes Spiel" - dafür wird ein neues Harness erstellt

## Userprofil
Lies `.opencode/state/user-profile.md` um zu wissen:
- Wie heißt das Kind?
- Wie alt ist es?
- Was mag es?

## Spielideen verwalten
Datei: `.opencode/state/spiel-ideen.md`

Nur für dieses Spiel:
- Features die hinzugefügt werden sollen
- Verbesserungen am aktuellen Spiel
- Bugfixes

Keine Ideen für andere/folgende Spiele!

## Aufgaben verwalten
Datei: `.opencode/state/aufgaben.md`

Struktur:
```markdown
# Aufgaben für [Spielname]

## Offen
- [ ] Aufgabe 1
- [ ] Aufgabe 2

## Erledigt
- [x] Aufgabe 0
```

## Regeln
- Erstelle immer zuerst das Userprofil wenn es nicht existiert
- Halte den aktuellen Spielstand aktuell
- Erstelle konkrete, kleine Aufgaben die ein Kind verstehen kann
- Nach der Planung anbieten den Plan zu speichern (vor dem Bauen)
