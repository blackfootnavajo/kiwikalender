Kalender & Dashboard 2025/2026

Übersicht

Diese Web-Anwendung ist ein interaktives Werkzeug zur Verwaltung von Terminen und Arbeitsstunden für die Jahre 2025 und 2026. Sie kombiniert eine übersichtliche Kalenderdarstellung mit einem leistungsstarken Dashboard zur statistischen Auswertung.

Hauptfunktionen

1. Duales Ansichtssystem

Dashboard: Bietet eine visuelle Auswertung Ihrer Daten mit Diagrammen (Chart.js). Es zeigt wöchentliche Termine, die Verteilung nach Wochentagen und (für 2026) eine detaillierte Stundenübersicht pro Woche.

Kalender: Eine klassische 12-Monats-Übersicht. Beim Wechsel in die Kalenderansicht springt die App automatisch zum aktuellen Monat des gewählten Jahres.

2. Daten-Tracking & Speicherung

Termine (2025/2026): Einfaches Markieren von Tagen.

Stunden-Erfassung (nur 2026): Ein modales Fenster ermöglicht die Eingabe von Arbeitsstunden pro Tag.

Persistenz: Alle Daten werden automatisch via localStorage im Browser gespeichert. Beim Schließen und Wiederöffnen der App bleiben Ihre Einträge erhalten.

3. Design & Bedienung

Dark Theme: Ein modernes, augenschonendes Design basierend auf der Farbe #2e3847.

Responsive Layout: Optimiert für Desktop und mobile Endgeräte (inklusive Swipe-Gesten zur Navigation zwischen Dashboard und Kalender).

Interaktive Statistiken: Dynamische Berechnung des Stundendurchschnitts basierend auf den tatsächlich geleisteten Arbeitstagen.

4. Datenmanagement

PDF-Export: Generiert eine druckoptimierte Übersicht des Kalenders.

JSON-Export/Import: Ermöglicht manuelle Backups oder den Transfer der Daten auf andere Geräte.

Jahr leeren: Funktion zum schnellen Löschen aller Markierungen eines spezifischen Jahres.

Technische Details

Frontend: HTML5, Tailwind CSS, JavaScript (ES6+).

Bibliotheken:

Chart.js für die Statistiken.

html2pdf.js für den PDF-Export.

Lucide / SVG-Icons für die Benutzeroberfläche.

Berechnungslogik: Verwendet die ISO-Wochenzählung zur korrekten Gruppierung von Daten in KW (Kalenderwochen).

Bedienungsanleitung

Jahr wählen: Nutzen Sie die Buttons oben links, um zwischen 2025 und 2026 zu wechseln.

Bearbeiten: Aktivieren Sie den "Bearbeiten"-Modus über das Zahnrad-Menü, um Tage zu markieren oder Stunden (2026) einzutragen.

Navigation: Klicken Sie auf die unteren Navigations-Buttons oder wischen Sie (auf mobilen Geräten) nach links/rechts, um die Ansicht zu wechseln.

Sicherung: Nutzen Sie regelmäßig den JSON-Export, um Ihre Daten extern zu sichern.

Hinweis: Diese Anwendung läuft vollständig clientseitig im Browser. Es werden keine Daten an einen externen Server übertragen.
