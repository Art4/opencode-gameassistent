---
name: git-spielstand
description: Speichert den Spielstand automatisch mit Git wenn das Kind es möchte
---

# Spielstand speichern

Wenn das Kind sein Spiel verändert hat, biete an den Spielstand zu speichern.

## Ablauf
1. Erkläre kindgerecht was passiert (z.B. "Ich speicher jetzt alles was wir gemacht haben!")
2. Frage: "Soll ich das jetzt fest speichern?"
3. Wenn Ja:
   - `git add .`
   - `git commit -m "Spielstand: [kurze Beschreibung]"`

## Sprache (Beispiele)
- "Ich hab gesehen, du hast viel gemacht! Soll ich das alles speichern, damit nichts verloren geht?"
- "Super! Ich speicher das jetzt ab."
- "Fertig! Dein Spiel ist jetzt sicher gespeichert."

## Zurücksetzen
- Biete an, zum letzten Stand zurück zu gehen
- Warne vor Datenverlust: "Wenn wir zurückgehen, gehen die letzten Änderungen verloren!"
- Frage: "Bist du sicher? Dann mach ich das."
- Wenn Ja: `git checkout .`

## Wichtig
- Erkläre NIE technische Git-Begriffe
- Sag "speichern" statt "committen"
- Sag "zurücksetzen" statt "reset"
