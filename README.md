# Kiosk Kasse PWA

Einfache, lokal gespeicherte Kassen-Web-App für iPhone. Enthält Artikelverwaltung, Suche/Barcodeeingabe, Warenkorb, Bestandsabzug, Rabatt, getrennte Zahlungserfassung, druckbaren Beleg, CSV-Import, Tagesverkäufe und JSON-Datensicherung.

## GitHub Pages veröffentlichen
1. Repository **Settings → Pages** öffnen.
2. Unter **Build and deployment** `Deploy from a branch` wählen.
3. Branch `main`, Ordner `/(root)` auswählen und speichern.
4. Warten, bis GitHub die Pages-Adresse anzeigt. Sie lautet voraussichtlich `https://ahmadigech-max.github.io/kiosk-kasse-pwa/`.
5. URL in Safari auf dem iPhone öffnen. Teilen → **Zum Home-Bildschirm** → **Hinzufügen**.

## Hinweise
- Daten liegen nur lokal in Safari auf diesem Gerät. Sie werden nicht automatisch synchronisiert; Sicherungen regelmässig exportieren.
- Kamerascan benötigt HTTPS und Browserunterstützung für `BarcodeDetector`. EAN-Barcode kann alternativ gesucht/eingegeben werden.
- Verkaufspreise gelten als brutto (inklusive Steuer); Steuersatz wird am Artikel gespeichert. Die MWST-Berechnung und Beleg sind nicht als Schweizer gesetzeskonforme Buchhaltungslösung zertifiziert.
- Vor echtem Geschäftsbetrieb bitte Testdaten verwenden, Sicherung einrichten und rechtliche/steuerliche Anforderungen in der Schweiz prüfen. Dies ist ein Prototyp, keine zertifizierte Registrierkasse.
