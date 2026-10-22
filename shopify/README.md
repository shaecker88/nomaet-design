# Shopify-Bausteine

Spiegel der eigenen Theme-Dateien (Theme "Horizon"), damit Änderungen nachvollziehbar sind.
Quelle der Wahrheit für die Optik bleibt `BRAND.md` und `tokens/`.

| Datei | Zweck |
|---|---|
| `snippets/nmt-logo.liquid` | Logo „nomaet.“ als Vektor, Farbe über `currentColor` |
| `sections/nmt-prelaunch.liquid` | Pre-Launch-Seite (Passwortseite): Statement, Warteliste, Story, Kapitel |
| `templates/password.json` | Passwortseite nutzt nur `nmt-prelaunch` |

Neue Kunden aus der Warteliste bekommen die Tags `newsletter, prelaunch`.
