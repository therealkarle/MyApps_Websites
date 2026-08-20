# Meine Apps & Websites

Willkommen! Dieses Repository zeigt meine datenschutzfreundlichen Ernährungs- und Leistungsanalyse-Tools.

## Sprache

- **English (Standard):** [README.md](./README.md)
- **Deutsch:** diese Seite

---

## Übersicht der öffentlichen Apps

| App | Zweck | Live-URL |
|-----|-------|----------|
| **[Fuel Lens](#fuel-lens)** | Ernährungsanalyse-Tool für das Verständnis von Ernährungsmustern, Trends und Biometrie | https://fuellens.vercel.app/?view=dashboard |
| **[Fuel Calc](#fuel-calc)** | Glukose:Fruktose-Verhältnis-Rechner für die Optimierung der Ernährung während Ausdauer Aktivitäten | https://fuelcalc-glucosefructos-ratio-calulator.lovable.app/ |

---

## GitHub-Repositories

| Repository | Beschreibung | GitHub-URL |
|------------|--------------|------------|
| **[TourTimeCalulator](#tourtlocalulator)** | Tourzeit-Vorhersagen mit Strava-API-Integration | https://github.com/therealkarle/TourTimeCalulator |
| **[SleepTempFinder](#sleeptempfinder)** | Schlaftemperatur (Und andere Raumdaten)-Korrelationsanalyse mit R | https://github.com/therealkarle/SleepTempFinder |
| **[RuterfahrenIn_BatchDateien](#ruterfahrenin_batchdateien)** | Windows-Batch-Skripte für geplantes PC-Herunterfahren | https://github.com/therealkarle/RuterfahrenIn_BatchDateien |
| **[ActivityWatch_StartUpScripts_FlorianZahl_launcher](#activitywatch_startupscripts_florianzahl_launcher)** | Startscript für meine ActivityWach Scrpits | https://github.com/therealkarle/ActivityWatch_StartUpScripts_FlorianZahl_launcher |
| **[ActivityWatch_Android-Import](#activitywatch_android-import)** | Google Drive zu ActivityWatch-Sync für Android | https://github.com/therealkarle/ActivityWatch_Android-Import |
| **[ActivityWatch_iPad_Simple_Screentime_import](#activitywatch_ipad_simple_screentime_import)** | iPad Screen Time zu ActivityWatch-Import | https://github.com/therealkarle/ActivityWatch_iPad_Simple_Screentime_import |
| **[ActivityWatch_email_summary](#activitywatch_email_summary)** | E-Mail-Berichte aus ActivityWatch-Daten | https://github.com/therealkarle/ActivityWatch_email_summary |
| **[ActivityWatch_iPad_sync_import](#activitywatch_ipad_sync_import)** | iPad zu PC ActivityWatch-Datensync | https://github.com/therealkarle/ActivityWatch_iPad_sync_import |
| **[YT-DLP-GUI](#yt-dlp-gui)** | GUI-Front-End für yt-dlp Video-Downloader | https://github.com/therealkarle/YT-DLP-GUI |
| **[PolarstepsPDFCreator](#polarstepspdfcreator)** | PDF-Reisedokumentation aus Polarsteps-Trips | https://github.com/therealkarle/PolarstepsPDFCreator |
| **[InternalWindMachine](#internalwindmachine)** | SimRacing-Telemetrie-basierter PC-Lüftercontroller | https://github.com/therealkarle/InternalWindMachine |

---

## [Fuel Lens](https://fuellens.vercel.app/?view=dashboard)

**Datenschutzfreundliche Ernährungs- und Gesundheitsanalyse-Website**

### Kernkonzept

Verwandeln Sie exportierte Lebensmittel-, Bewegungs-, Gewichts- und Biometrie-Daten in verständliche Dashboards, Trends, Vergleiche, Ziele und Berichte — alles lokal in Ihrem Browser verarbeitet.

> Helfen Sie Benutzern zu verstehen, wie ihre Nahrungsaufnahme, Nährstoffbalance, Aktivität, Körpermessungen und Energieverbrauch über die Zeit zusammenhängen.

### Hauptfunktionen

#### 📥 Datenimport
- **Unterstützte Quellen:** Cronometer, FatSecret, FatSecret API, MyFitnessPal
- **Formate:** CSV, XLSX/XLS, PDF-Tagesberichte
- **Funktionen:** Drag-and-drop für Dateien/Ordner, automatische Erkennung, passwortgeschützte Arbeitsmappen
- **Datentypen:** Tägliche Nährstoffzusammenfassungen, einzelne Lebensmittelportionen, Trainingseinheiten, Gewicht/Biometrie, Mahlzeiten

#### 📊 Dashboard
Schneller Überblick über:
- Aufgenommene Kalorien, Energiebilanz, Kalorienlücke
- Trainingskalorien und geschätzter Verbrauch
- Fortschritt bei Protein, Kohlenhydraten und Fett
- Nährstoffziel-Erreichung und Verhältnisse
- Adaptive TDEE-Kontext
- Top-Lebensmittel-Beiträge

#### 📅 Tagesbuch
Fokus auf einen ausgewählten Tag:
- Lebensmittel und Portionen mit Nährstoff-Gesamtwerten
- Energieaufnahme und Training
- Gewicht und Biometrie-Messwerte
- Fortschritt gegenüber Nährstoffzielen
- Sowohl nährstoff- als auch lebensmittelfokussierte Ansichten

#### 📈 Nährstoff-Tracks
Verfolgen Sie fast jeden Nährstoff über die Zeit:
- Täglich, wöchentlich, vierwöchentlich, quartalsweise, semesterweise und jährlich
- Durchschnitts-Referenzlinien
- Ziel und DRI-Kontext
- Durchsuchbare Nährstoffauswahl
- Datumsnavigation und Bereichssteuerung

#### 📉 Biometrische Trends
Messungen wie folgt darstellen:
- Gewicht, Körperfett, Körpermaße
- Herzfrequenz, Ruheherzfrequenz, HRV
- Schlafbezogene Metriken
- Importierte biometrische Reihen
- Trends mit Zielen vergleichen

#### 🔥 Adaptive TDEE-Analyse
Schätzen Sie den Gesamtenergieverbrauch durch Vergleich:
- Protokollte Kalorienaufnahme
- Gewichtsänderungen und geglättete Trends
- Körperzusammensetzung
- Trainingsinformationen

Unterstützt:
- First Principles TDEE
- Statistische TDEE
- BMR-basierte Fallback-Berechnungen
- Aktivitätsniveau-Annahmen
- Konfidenz- und Datenabdeckungsindikatoren

*Als Planungsschätzung gedacht, nicht als medizinische Beurteilung.*

#### 🎯 Zielverwaltung
Konfigurieren Sie:
- Tägliche Kalorienziele
- Protein-, Kohlenhydrat-, Fettziele
- Mikronährstoff-Minima und -Maxima
- Nährstoffverhältnisse und Sichtbarkeit
- Zielband-Ränder

Makroziele basierend auf:
- Prozentualen Verhältnissen
- Festen Grammwerten
- Keto-Berechnungen
- Magere Körpermasse und Zusammensetzung
- Trainingsbasierte Kohlenhydrat-Boni

#### 📐 Nährstoffverhältnisse
Verfolgen Sie Beziehungen wie:
- Omega-6 / Omega-3
- Zink / Kupfer
- Kalium / Natrium
- Calcium / Magnesium
- Calcium / Oxalat
- Fett als Prozentsatz der Kalorien
- Benutzerdefinierte Nährstoffverhältnisse

#### 🔍 Lebensmittel-Browser & Vergleich
- Suchen und durchsuchen importierte Lebensmittel
- Nährstoffdetails innerhalb von Datumsbereichen prüfen
- Lebensmittel Seite an Seite vergleichen
- Pro 100g oder pro 100 Kalorien
- Ranglisten, Medaillen, Kategorienwerte
- Datenabdeckungsindikatoren

#### 🏅 Nährstoffdichte-Bewertung
Mehrere Bewertungssysteme:
- Benutzerdefiniertes exponentielles Modell
- NRF 9, 15, 21, 26 Varianten

Berücksichtigt:
- Positive Nährstoffe
- Nährstoffe zum Begrenzen
- Kategoriegewichtung
- Fehlende Datenabdeckung
- Diminishing Returns

#### 🏥 Medizinischer Berichts-Manager
Erstellen Sie strukturierte Berichte für Gesundheitsgespräche:
- Dashboard-Zusammenfassung
- Energie, Makros, Mikronährstoffe
- Mahlzeiten und Tagebuch
- Biometrie und Diagramme
- Konfigurierbare Abschnitte, Datumsbereiche, Aggregation
- Export/Druck als PDF

*Entwickelt, um medizinische Gespräche zu unterstützen, nicht Zustände zu diagnostizieren.*

#### 🤖 KI-Kontext-Export
Erstellen Sie kompakte CSV mit:
- Ausgewählten Nährstoffen, Kalorien, Training
- Gewicht, Körperfett, Schlaf, Herzfrequenz-Metriken
- Tägliche oder wöchentliche Aggregation
- Vorschau der Ausgabe zur Überprüfung

*Überprüfen Sie vor dem Teilen — kann sensible Gesundheitsinformationen enthalten.*

#### 🔒 Datenspeicherung & Datenschutz
Client-seitiges Verarbeitungsmodell:
- Daten im Browser speichern
- Gespeicherte Sitzungen laden
- Vollständige Backups exportieren/importieren
- Gespeicherte Daten und Einstellungen löschen
- **Gesundheitsdaten bleiben während der normalen Nutzung im Browser**
- Berechnungen und Diagramme lokal ausführen
- Keine Backend-Übertragung für Produktionsanalyse erforderlich

*Behandeln Sie Backup-Dateien, medizinische Berichte und KI-Exporte als sensible persönliche Gesundheitsdateien.*

#### 📚 Integrierte Dokumentation
Umfassendes [Wiki](https://fuellens.vercel.app/wiki) mit Anleitungen für jede Funktion, jedes Konzept und jeden Workflow in Fuel Lens — vom ersten Import bis zur erweiterten Analytik.

### Vorgesehener Workflow

1. Exportieren Sie Ernährungs-/Gesundheitsdaten aus unterstützter App
2. Laden Sie Dateien hoch oder verbinden Sie FatSecret
3. Überprüfen Sie importierte Daten
4. Konfigurieren Sie Ziele (Kalorien, Makros, Nährstoffe, Verhältnisse, Bewertung)
5. Verwenden Sie Dashboard für schnellen Überblick
6. Untersuchen Sie Trends, Lebensmittel, Biometrie, TDEE
7. Vergleichen Sie Lebensmittel oder erstellen Sie Berichte
8. Exportieren Sie Backup, medizinischen Bericht oder KI-Analyse-Datensatz bei Bedarf

**Kurz gesagt:** Fuel Lens ist ein persönlicher Ernährungsanalyse-Arbeitsbereich — privat, datengetrieben, anpassbar und nützlich für die langfristige Überprüfung von Ernährungs- und Gesundheitsmustern.

---

## [Fuel Calc](https://fuelcalc-glucosefructos-ratio-calulator.lovable.app/)

**Glukose:Fruktose-Verhältnis-Rechner für Ausdauer-Befüllung**

### Kernkonzept

Geben Sie interne Zuckerwerte (Glukose, Fruktose, Saccharose, Stärke) aus Cronometer ein, um optimale Befüllungsverhältnisse für Radfahren, Laufen und Triathlon zu finden.

### So funktioniert es

1. **Zucker eingeben:** Glukose, Fruktose, Saccharose, Stärke, Maltose, Laktose, Galaktose, Allulose
2. **Voreinstellung wählen:** 1:0.80, 1:1 oder 2:1 Verhältnis
3. **Maßnahmenplan erhalten:** Rechner sagt Ihnen, wie viel Glukose oder Fruktose hinzuzufügen ist
4. **Strategie optimieren:** Fügt Glukose oder Fruktose hinzu, um Ziel zu erreichen, während bestehende Mengen berücksichtigt werden

### Verwendung mit Cronometer

1. Cronometer-Tagebuch öffnen → **Trends**-Registerkarte
2. **Glukose**, **Fruktose**, **Saccharose**, **Stärke** im Nährstoffbericht aktivieren
3. Grammwerte für Mahlzeit/Tag/Trainingsfenster kopieren
4. In Rechner einfügen und Voreinstellung wählen
5. Maßnahmenplan folgen, um Zucker hinzuzufügen oder zu tauschen, bis Zielverhältnis erreicht ist

### Zuckerarten erklärt

| Zucker | Beschreibung | Beitrag |
|--------|--------------|---------|
| **Glukose** | Einfachste Form, absorbiert über SGLT1. Hauptbrennstoff für Muskeln/Gehirn während des Trainings. | 100% Glukose-Seite |
| **Fruktose** | Fruchtzucker über GLUT5-Transporter. Läuft parallel, erhöht Gesamtkohlenhydrat-Oxidation. | 100% Fruktose-Seite |
| **Saccharose** | Haushaltszucker: 1 Glukose + 1 Fruktose verbunden. | Geteilt: 0,5g Glukose + 0,5g Fruktose |
| **Stärke** | Komplexes Kohlenhydrat (lange Glukoseketten). Verdauung baut zu Glukose ab. | 100% Glukose-Seite |
| **Maltose** | Zwei Glukoseeinheiten verbunden. Schnell zu Glukose abgebaut. | 100% Glukose-Seite |
| **Laktose** | Milchzucker: Glukose + Galaktose. Galaktose verwendet SGLT1. | 100% Glukose-Seite |
| **Galaktose** | Einfacher Zucker in Milch/Produkten. Verwendet SGLT1-Transporter. | 100% Glukose-Seite |
| **Allulose** | Seltener, kalorienarmer Zucker, der nicht für Energie metabolisiert wird. | Vom Verhältnis ausgeschlossen |

### Wissenschaftlicher Hintergrund

Das Glukose-zu-Fruktose-Verhältnis ist entscheidend für die intestinale Absorption:

- **SGLT1-Transporter** bewegen Glukose, sättigen bei ~60–90 g/h
- **Hinzufügen von Fruktose** aktiviert GLUT5-Transporter (läuft parallel)
- **Gesamtkohlenhydrat-Oxidation** kann 90–120 g/h erreichen
- **1:0.8 Verhältnis** (aktuelle Forschung) reduziert GI-Beschwerden gegenüber älterem 2:1-Standard bei gleichzeitiger Maximierung der Treibstoffverfügbarkeit

### Funktionen

- **Echtzeit-Verhältnisberechnung** mit aktuellem vs. Ziel-Vergleich
- **Maßnahmenplan** mit präzisen Empfehlungen
- **Optimierungsstrategie**, die bestehende Aufnahme bewahrt
- **OCR-Unterstützung:** Ernährungsscreenshots hochladen oder einfügen (Strg/Cmd+V) für automatische Wertextrahierung
  - 100% Offline-Verarbeitung (kostenlos, kein Bild-Upload)
  - Erster Download lädt OCR-Engine einmalig herunter
- **Funktioniert mit jedem Nährstoff-Tracker**, der Zuckeraufschlüsselung bietet
- **Behandelt Randfälle**, wenn Glukose oder Fruktose null ist

---

## Technologie & Datenschutz

Beide Apps teilen Grundprinzipien:

✅ **Client-seitige Verarbeitung** — Ihre Daten bleiben in Ihrem Browser  
✅ **Datenschutz zuerst** — Berechnungen lokal ausführen  
✅ **Offener Zugang** — browserbasiert, keine Installation oder Registrierung erforderlich

---

## Details zu GitHub-Repositories

<a id="tourtlocalulator"></a>
### [TourTimeCalulator](https://github.com/therealkarle/TourTimeCalulator)

Python-basierter Tourzeit-Rechner mit Strava-API-Integration. Sagt Tour-Abschlusszeiten voraus und synchronisiert Aktivitäten mit Ihrem Strava-Konto.

**Hauptfunktionen:**
- Strava-Aktivitätssynchronisation
- Tourzeit-Vorhersagen und Berechnungen
- Plattformübergreifende Unterstützung (Windows, macOS, Linux)

**Technologie:** Python 3.11+

---

### [SleepTempFinder](https://github.com/therealkarle/SleepTempFinder)

Analysiert Korrelationen zwischen Schlafzimmertemperatur und Luftfeuchtigkeit mit Schlafqualitätsmetriken. Hilft, optimale Schlafbedingungen zu identifizieren.

**Hauptfunktionen:**
- Schlafscore-Korrelationsanalyse
- Ruheherzfrequenz (RHR)-Tracking
- Herzfrequenzvariabilität (HRV)-Analyse

**Technologie:** R-Sprache

---

### [RuterfahrenIn_BatchDateien](https://github.com/therealkarle/RuterfahrenIn_BatchDateien)

Windows-Batch-Skripte für geplanten PC-Herunterfahren oder Ruhezustand. Automatisiert die Energieverwaltung nach einer angegebenen Dauer.

**Hauptfunktionen:**
- Konfigurierbare Timer für Herunterfahren/Ruhezustand
- Einfache Ausführung über Verknüpfung oder Befehlszeile
- Keine zusätzliche Software erforderlich

**Technologie:** Windows Batch

---

### [ActivityWatch_StartUpScripts_FlorianZahl_launcher](https://github.com/therealkarle/ActivityWatch_StartUpScripts_FlorianZahl_launcher)

Orchestriert den Start mehrerer ActivityWatch-Worker-Prozesse beim Systemstart, um eine zuverlässige Datenerfassung zu gewährleisten.

**Hauptfunktionen:**
- Automatischer Start aller erforderlichen ActivityWatch-Dienste
- Konfigurierbare Verzögerungen zwischen Starts
- Statusbenachrichtigungen

**Technologie:** Python 3.11+

---

### [ActivityWatch_Android-Import](https://github.com/therealkarle/ActivityWatch_Android-Import)

Synchronisiert automatisch Aktivitätsdaten von Google Drive mit ActivityWatch, um Android-Nutzungsdaten nahtlos zu importieren.

**Hauptfunktionen:**
- Automatische Google Drive-Überwachung
- Import verschiedener Aktivitätstypen
- Konflikterkennung und Zusammenführung

**Technologie:** Python 3.11+

---

### [ActivityWatch_iPad_Simple_Screentime_import](https://github.com/therealkarle/ActivityWatch_iPad_Simple_Screentime_import)

Importiert iPad-Bildschirmzeitdaten direkt in ActivityWatch für umfassende Produktivitätsanalysen.

**Hauptfunktionen:**
- Einfache CSV-Konvertierung
- Unterstützung für verschiedene iPadOS-Versionen
- Integration mit ActivityWatch-Datenbank

**Technologie:** Python 3.11+

---

### [ActivityWatch_email_summary](https://github.com/therealkarle/ActivityWatch_email_summary)

Generiert regelmäßige E-Mail-Berichte basierend auf ActivityWatch-Daten, um Produktivitätstracks zu verfolgen.

**Hauptfunktionen:**
- Konfigurierbare Berichtszeiträume
- Anpassbare Metriken und Visualisierungen
- E-Mail-Benachrichtigungen

**Technologie:** Python 3.11+

---

### [ActivityWatch_iPad_sync_import](https://github.com/therealkarle/ActivityWatch_iPad_sync_import)

Synchronisiert iPad-Daten mit ActivityWatch auf dem PC für konsistente Aktivitätsverfolgung über Geräte hinweg.

**Hauptfunktionen:**
- Bidirektionale Synchronisation
- Konfliktauflösung
- Automatische Erkennung neuer Daten

**Technologie:** Python 3.11+

---

### [YT-DLP-GUI](https://github.com/therealkarle/YT-DLP-GUI)

Eine benutzerfreundliche grafische Oberfläche für den leistungsstarken yt-dlp Video-Downloader.

**Hauptfunktionen:**
- Batch-Downloads
- Format- und Qualitätsauswahl
- Playlist-Unterstützung
- Fortschrittsverfolgung

**Technologie:** Python 3.11+ mit PyQt

---

### [PolarstepsPDFCreator](https://github.com/therealkarle/PolarstepsPDFCreator)

Erstellt professionelle PDF-Reisedokumentationen aus Polarsteps-Reisedaten mit anpassbaren Vorlagen.

**Hauptfunktionen:**
- Automatische Fotoverarbeitung
- Kartengenerierung
- Textlayout-Anpassung
- Offline-Export

**Technologie:** Python 3.11+

---

### [InternalWindMachine](https://github.com/therealkarle/InternalWindMachine)

Ein SimRacing-Telemetrie-basierter PC-Lüftercontroller, der Lüftergeschwindigkeiten basierend auf Rennbedingungen anpasst.

**Hauptfunktionen:**
- Echtzeit-Telemetrie-Integration
- Anpassbare Lüfterkurven
- Multi-Sensor-Unterstützung
- Automatische und manuelle Modi

**Technologie:** Python 3.11+

