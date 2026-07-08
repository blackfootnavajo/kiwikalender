# Kalender & Dashboard 2025/2026/2027

Eine moderne, webbasierte Anwendung zur Verwaltung von Terminen und Arbeitsstunden für die Jahre 2025 bis 2027. Diese App läuft vollständig im Browser und speichert alle Daten lokal auf deinem Gerät.

🌟 Funktionen

📅 Kalender

Jahresübersicht: Wechseln Sie nahtlos zwischen den Jahren 2025, 2026 und 2027.

Interaktive Tage: Markieren Sie Tage durch einfaches Anklicken (im Bearbeitungsmodus).

Farbauswahl: Wählen Sie zwischen drei Markierungsmustern:
- **Orange**: Klassische Hervorhebung (ersetzt das alte Rot).
- **Rot**: Eine dezentere rote Markierung (ersetzt das alte Violett).
- **Weiß-Rot (Japan-Style)**: Ein neues Muster mit weißem Hintergrund und einem roten Quadrat in der Mitte (neuer Standard).

Stundenerfassung (2026+): Für die Jahre 2026 und 2027 können spezifische Stunden pro Tag erfasst werden.

Heute-Hervorhebung: Der aktuelle Tag wird im Kalender mit einer blauen Umrandung hervorgehoben.

Detailansicht: Klicken Sie auf markierte Tage (außerhalb des Bearbeitungsmodus), um Details einzusehen (Read-Only).

📊 Dashboard

Statistiken: Visualisierung Ihrer Daten durch interaktive Diagramme (Chart.js).

Wöchentliche Termine: Linien-Diagramm zur Übersicht der Auslastung über die Kalenderwochen.

Wochentagsverteilung: Balkendiagramm zur Analyse der Verteilung auf Wochentage (Mo-So).

KPIs: Anzeige der durchschnittlichen Tage pro Woche und (für 2026+) der durchschnittlichen Stunden pro Arbeitstag.

Stundenübersicht: Balkendiagramm der geleisteten Stunden pro Kalenderwoche.

🛠️ Tools & Verwaltung

Daten-Persistenz: Alle Eingaben werden automatisch im localStorage des Browsers gespeichert.

PDF Export: Erstellen Sie mit einem Klick eine PDF-Datei Ihrer aktuellen Ansicht.

Backup System: Exportieren Sie Ihre Daten als JSON-Datei und importieren Sie diese auf anderen Geräten.

Responsive Design: Optimiert für Desktop und Mobile (inkl. Swipe-Gesten zum Wechseln der Ansichten auf Touchscreens).

Dropdown Navigation: Kompakte Steuerung für Jahre und Einstellungen, optimiert für mobile Endgeräte.

Dark Mode: Augenschonendes, dunkles Farbschema.

🚀 Nutzung

Starten: Öffnen Sie einfach die index.html Datei in einem modernen Webbrowser.

Navigation:
- Nutzen Sie die Buttons oben (Dashboard/Kalender) zum Wechseln der Ansicht.
- Auf Mobilgeräten können Sie auch nach links oder rechts wischen.
- Das Jahr und die Einstellungen können über die Menüs unten gesteuert werden.

Bearbeiten:
- Aktivieren Sie den Bearbeitungsmodus über das Stift-Symbol unten rechts.
- Klicken Sie auf Tage im Kalender, um sie zu markieren, die Farbe zu wählen oder Stunden (ab 2026) einzutragen.

Daten sichern:
- Nutzen Sie das Menü unten rechts (Zahnrad), um ein Backup (JSON) zu erstellen oder als PDF zu drucken.

💻 Technologien

- HTML5 / JavaScript
- Tailwind CSS (Styling via CDN)
- Chart.js (Diagramme)
- html2pdf.js (PDF Generierung)
- Inter Font (Google Fonts)

⚠️ Hinweis

Da die Daten im localStorage Ihres Browsers gespeichert werden, gehen diese verloren, wenn Sie den Browser-Cache leeren. Nutzen Sie regelmäßig die JSON Export Funktion, um Ihre Daten dauerhaft zu sichern.
