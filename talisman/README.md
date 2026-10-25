# ✦ Talisman

Ein tägliches Reflexions-Formular im Stil von Google Forms. Es führt Schritt für Schritt durch:

1. 🌙 **Was hast du geträumt?**
2. 🙏 **Wofür bist du dankbar?** (3 Stück)
3. 🌟 **Wofür lobst du dich?** (3 Stück) → **Absenden**
4. 💭 **Emotionen**: Wut, Trauer, ? → **Absenden**

Jede Eingabe wird sofort im Browser zwischengespeichert, auch schon beim ersten Schritt. Beim Neuladen geht nichts verloren.
Beim Absenden entsteht eine Markdown-Datei `JJJJ-MM-TT Talisman.md`. Beim zweiten Absenden wird dieselbe Datei um die Emotionen ergänzt.

## Benutzung

`index.html` in **Chrome oder Edge** öffnen (Doppelklick reicht, kein Server nötig).

Einmalig auf **„Obsidian-Ordner wählen“** klicken und den Zielordner in deinem Vault auswählen, z. B. `Vault/Journal/Talisman`.
Der Browser merkt sich den Ordner. Danach landen die Dateien direkt dort. Eventuell fragt der Browser beim Speichern noch einmal kurz nach der Berechtigung.

Ohne gewählten Ordner, oder in Browsern wie Firefox und Safari, wird die Datei stattdessen heruntergeladen.

## Beispiel-Ausgabe

```markdown
---
date: 2026-10-25
tags: [talisman, journal]
---

# Talisman – 25.10.2026

## 🌙 Traum
…

## 🙏 Dankbarkeit
1. …
2. …
3. …

## 🌟 Selbstlob
1. …

## 💭 Emotionen
### Wut
…
```
