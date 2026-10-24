# Changelog

Alle Versionen von Book of Colors. Format nach [Keep a Changelog](https://keepachangelog.com/de/1.1.0/), Versionen nach [SemVer](https://semver.org/lang/de/).

## [1.3.0] – 2026-10-24

### Ort, Zeit und Notiz
- Aufnahmezeit und Ort werden aus den Foto-Daten (EXIF) gelesen; der Ortsname wird offline auf dem Gerät ermittelt.
- Nach dem Anlegen fragt die App: „Möchtest du etwas zum Bild notieren?“ – Ort, Zeit und Notiz, alles optional, auch per Diktat über die Tastatur.
- Ohne Ortsangabe im Foto: aktuellen Standort auf Wunsch übernehmen.
- Seitenansicht mit „Notieren“ und Link zur Karte; Ort und Datum stehen auf der Seite und auf geteilten Bildern.
- Suche findet auch Orte und Notizen.

### Kartei
- App-Kopfleiste statt großem Titelkopf: Logo, Titel und Anzahl in einer Zeile, mehr Platz für die Kartei.
- Karten: jede Seite fast bildschirmfüllend, seitlich wischen, mit Position „3 von 12“; zurück aus einer Seite landet man auf derselben Karte.
- Drei Ansichten per Umschalter: Karten, Raster, Liste mit Vorschaubild und Farbstreifen.
- Rasterkarten wie eine kleine Buchseite: Nummer links, Haarlinie, rechts Farben und Namen.
- Schmaler Sicherungshinweis, Monatsüberschriften bleiben beim Scrollen stehen.

### Recht
- Ortsnamen aus GeoNames (CC BY 4.0), Nachweis unter Rechtliches.

## [1.2.0] – 2026-10-24

### Teilen
- Seite als gestaltetes Bild teilen: Beitrag (4:5), Story (9:16) oder Karteiseite, mit Vorschau.
- Farbprofil teilen: als Bild mit prägenden Farben und Kombinationen, oder als Link. Wer den Link öffnet, sieht die Kombinationen und kann sie übernehmen. Der Link enthält nur Farben, keine Fotos.

### Sichern
- Ziel je nach Gerät: iPhone → iCloud Drive, Android → Google Drive, am Rechner Speichern-Dialog.
- Hinweis in der Kartei, wenn neue Seiten noch nicht gesichert sind.

### Bedienung
- Kartei mit Suche, Farbfiltern und Monatsgruppen; gedrückt halten öffnet Teilen, Bearbeiten, Löschen.
- Seitenansicht mit Werkzeugleiste, Löschen mit Bestätigung.
- Farben als durchsuchbare Liste: „In deiner Kartei“ nach Häufigkeit oder alle nach Farbfamilien.
- Sichern als Statuskarte mit Listen; Leisten zeigen beim Scrollen den Seitentitel.
- Größere Tippflächen und Schrift, Knöpfe in normaler Schreibweise.

## [1.1.0] – 2026-10-24

### Bedienung wie eine native App
- Tab-Leiste unten: Kartei, Farben, Neue Seite, Sichern, Mehr.
- Neue Seite öffnet ein Auswahl-Blatt: Live-Sucher oder Foto aus der Mediathek.
- Unterseiten gleiten herein, mit Zurück-Titel der vorigen Ansicht; Editor und Live-Sucher öffnen als Vollbild.
- Zurück-Geste und Browser-Zurück folgen dem Verlauf.
- In der Seitenansicht wischen für vorige und nächste Seite.
- „Mehr“ bündelt Ansicht, Reihenfolge, Hilfe und Info.

### Einführung
- Kurze Einführung beim ersten Start in vier Schritten, jederzeit unter Mehr erneut aufrufbar.
- Hinweis vor der Kamera-Freigabe.
- Installations-Hinweis für iPhone, Mac und Chrome.

### Vorbereitung App-Wrapper
- `npm run build:app` erzeugt `dist-app/` für Capacitor, Anleitung in `WRAPPER.md`.

## [1.0.0] – 2026-10-23

Erste veröffentlichte Version.

### Funktionen
- Live-Sucher: Die Palette (2–5 Farben) folgt dem Kamerabild, Festhalten übernimmt Foto, Ausschnitt und Farben.
- Foto aus der Mediathek wählen, am Mac auch ins Fenster ziehen oder mit ⌘V einfügen.
- Bildausschnitt wählen, auch nachträglich; das Original bleibt erhalten.
- Farberkennung, die Kanten und große neutrale Hintergründe ausblendet; Farbvorschläge aus dem Foto und Pipette mit Lupe.
- Anordnungen Reihe, Kreuz und Feld; Farbnamen aus einer eigenen deutschen Namensliste.
- Kartei als Raster oder Buch, Farbnamen-Verzeichnis mit Filter.
- Seite als Bild sichern; Sicherung der ganzen Kartei als Datei, etwa in iCloud Drive.
- Offline nutzbar, auf iPhone und Mac als App installierbar.

### Datenschutz und Recht
- Alle Daten bleiben auf dem Gerät; keine Cookies, kein Tracking, keine Anfragen an Dritte.
- Schriften selbst gehostet (SIL Open Font License 1.1).
- Ansicht „Rechtliches“ mit Impressum, Datenschutz, Nutzung und Lizenzen.
