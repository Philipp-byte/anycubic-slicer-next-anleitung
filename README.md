# Anycubic Slicer Next – Bedienung Schritt für Schritt

Eine bebilderte Schülerhandreichung für den 3D-Druck-Unterricht am
**Berufskolleg Wirtschaftsinformatik (BKWI)** der **Kolping Bildung**.

Die Anleitung führt vom 3D-Modell bis zur fertigen Druckdatei – mit
Screenshots aus der real installierten Programmversion, erklärten
Fachbegriffen, Checklisten und Übungsaufgaben mit Lösung.

**➡️ [Anleitung online lesen](https://Philipp-byte.github.io/anycubic-slicer-next-anleitung/)**

---

## Eckdaten

| | |
|---|---|
| Zielgruppe | BKWI, Anfängerinnen und Anfänger ohne Vorkenntnisse |
| Drucker | Anycubic Kobra 3 · 0,4 mm Düse |
| Filament | Anycubic PLA |
| Beispielobjekt | Schlüsselanhänger „Kolping Bildung BKWI" |
| Umfang | 21 Kapitel, 45 Abbildungen, 7 animierte Ablaufsequenzen |
| Bearbeitungszeit | ca. 45–90 Minuten |

## Inhalt

**Grundlagen**
1. Was macht ein Slicer eigentlich?
2. Das Programm starten
3. Die Oberfläche kennenlernen

**Der Arbeitsablauf**

4. Das 3D-Modell importieren
5. Drucker und Druckbett prüfen
6. Das Filament auswählen · Das Modell einfärben
7. Prozessprofil und Schichthöhe
8. Das Objekt ausrichten – bewegen, drehen, skalieren *(inkl. Negativbeispiel)*

**Feineinstellungen**

9. Wände und Schalen
10. Die Füllung (Infill)
11. Stützstrukturen
12. Haftung: Saum und Umrandung

**Abschluss**

13. Slicen
14. Die Vorschau auswerten
15. Die Druckdatei exportieren

**Drucker & Gerät**

16. Der Reiter *Werkbank*
17. Das Menü *Kalibrierung*

**Material**

18. Checklisten
19. Aufgaben mit Lösungen
20. Typische Fehlerbilder
21. Glossar (26 Fachbegriffe)

## Didaktische Besonderheiten

- **Gemessen statt behauptet.** Skalierung und Ausrichtung werden nicht nur
  erklärt, sondern mit echten Slicer-Werten belegt: 100 % gegen 214 %
  (Material ×6,1, Zeit ×4,9) und flach liegend gegen 47,6° gekippt
  (272 statt 20 Schichten, 1,07 g Stützmaterial für den Müll).
- **Schichtaufbau sichtbar gemacht.** Eine Bildserie von Schicht 1 bis 20
  zeigt: massiver Boden → Gitterfüllung → massiver Deckel.
- **Volltextsuche** über alle Kapitel, auch ohne Umlaute
  (`stuetzen` findet `Stützen`). Mit `Strg` + `F` oder `/` erreichbar.
- **Anklickbare Checklisten** und Aufgaben mit aufklappbarer Lösung.
- **Druckfertig:** Ein eigenes Druck-Stylesheet blendet Navigation und
  Suchleiste aus und verhindert Seitenumbrüche mitten in Abbildungen.

## Verwendung im Unterricht

Die Datei ist vollständig statisch – kein Server, keine Abhängigkeiten,
keine Internetverbindung nötig.

- **Online:** über GitHub Pages (Link oben).
- **Offline:** Repository als ZIP herunterladen, entpacken,
  `index.html` im Browser öffnen.
- **Moodle:** `index.html`, `anleitung.html` und den Ordner `bilder`
  gemeinsam als ZIP hochladen und als Verzeichnis entpacken lassen.
- **Ausdruck:** `anleitung.html` öffnen, dann `Strg` + `P`.

> **Wichtig:** Der Ordner `bilder` muss immer neben den HTML-Dateien liegen,
> sonst fehlen alle Abbildungen.

## Aufbau des Repositorys

```
.
├── index.html      Startseite ("Start Learning", BKWI-Logo, Animationen)
├── anleitung.html  Die vollständige Anleitung (eine Datei, alles inline)
├── bilder/         49 Abbildungen, 7 GIF-Sequenzen, Logos
├── .nojekyll       Verhindert die Jekyll-Verarbeitung auf GitHub Pages
├── LICENSE
└── README.md
```

Die Startseite ist reines HTML/CSS/JS ohne externe Bibliotheken. Der
Sound-Effekt beim Start wird über die Web Audio API erzeugt – es gibt
also keine Audiodateien. Über den Lautsprecher-Knopf oben rechts lässt
er sich abschalten; die Einstellung wird im Browser gespeichert.

## GitHub Pages aktivieren

1. **Settings** → **Pages**
2. Bei *Source* **Deploy from a branch** wählen
3. Branch **main**, Ordner **/ (root)** → **Save**
4. Nach ein bis zwei Minuten ist die Seite unter
   `https://Philipp-byte.github.io/anycubic-slicer-next-anleitung/` erreichbar

## Lizenz

[CC BY-NC-SA 4.0](LICENSE) – Weitergabe und Bearbeitung für nicht
kommerzielle Bildungszwecke erlaubt, bei Namensnennung und unter gleichen
Bedingungen.

Die Screenshots zeigen die Benutzeroberfläche des *Anycubic Slicer Next*.
Alle Marken- und Produktbezeichnungen gehören ihren jeweiligen Inhabern.
Diese Anleitung ist ein unabhängiges Unterrichtsmaterial und steht in keiner
Verbindung zu Anycubic.

---

Kolping Bildung · BKWI · Riegert
