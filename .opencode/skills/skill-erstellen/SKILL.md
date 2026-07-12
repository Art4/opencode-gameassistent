---
name: skill-erstellen
description: Erstellt neue Skills wenn spezifische Funktionalitäten eine eigene Anleitung benötigen
---

# Skill erstellen

Wenn ein neuer Skill benötigt wird (z.B. für Partikeleffekte, Sound, Kollision):

## Schritte
1. Erstelle Ordner `.opencode/skills/<skill-name>/`
2. Erstelle `SKILL.md` mit:
   - Frontmatter (name, description)
   - Klare Anleitung auf Deutsch
   - Kindgerechte Sprache
3. Teste ob der Skill funktioniert

## Frontmatter Vorlage

```markdown
---
name: skill-name
description: Kurze Beschreibung wann dieser Skill verwendet wird
---

# Skill Titel

Anleitung auf Deutsch...
```

## Skill-Namen
- Kleinbuchstaben mit Bindestrichen
- z.B. `partikeleffekte`, `sound-hinzufuegen`, `kollision`

## Beispiele für nützliche Skills
- Partikeleffekte (Feuer, Rauch, Sterne)
- Sound und Musik
- Kollisionserkennung
- Scenen-Wechsel
- Highscore-System
