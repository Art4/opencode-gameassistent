---
name: phaser-skeleton
description: Erstellt eine neue Phaser.js Spielstruktur mit index.html und game.js
---

# Phaser.js Skeleton erstellen

Wenn ein Kind ein neues Spiel erstellen möchte, erstelle diese Struktur:

## Schritte
1. Erstelle `index.html` mit Phaser CDN
2. Erstelle `js/game.js` mit Grundstruktur
3. Erstelle leeren `assets/` Ordner
4. Aktualisiere `.opencode/state/spiel-ideen.md` mit dem neuen Spiel
5. Erstelle erste Aufgaben in `.opencode/state/aufgaben.md`

## index.html Vorlage

```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SPIELNAME</title>
    <script src="https://cdn.jsdelivr.net/npm/phaser@3.80.1/dist/phaser.min.js"></script>
    <style>
        body { margin: 0; padding: 0; background: #000; }
    </style>
</head>
<body>
    <script src="js/game.js"></script>
</body>
</html>
```

Ersetze `SPIELNAME` mit dem Namen den das Kind gewählt hat.

## game.js Vorlage

```javascript
// Spielkonfiguration
const config = {
    type: Phaser.AUTO,
    width: 800,
    height: 600,
    backgroundColor: '#2d2d2d',
    scene: {
        preload: preload,
        create: create,
        update: update
    }
};

// Spiel starten
const game = new Phaser.Game(config);

// Bilder laden
function preload() {
    // Hier Bilder laden, z.B.:
    // this.load.image('spieler', 'assets/spieler.png');
}

// Spiel initialisieren
function create() {
    // Hier Spiellogik einbauen
    this.add.text(400, 300, 'Dein Spiel!', {
        fontSize: '32px',
        fill: '#ffffff'
    }).setOrigin(0.5);
}

// Spiel aktualisieren (wird 60x pro Sekunde aufgerufen)
function update() {
    // Hier Bewegungen und Logik aktualisieren
}
```
