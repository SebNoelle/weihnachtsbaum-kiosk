# Weihnachtsbaum-Berater · Kiosk-Prototyp

Eigenständiges Single-File-HTML für den iPad-Kiosk im Gartencenter
Brockmeyer: Baum-Berater (Größe, Optik, Modell) inklusive Licht- und
Schmuckmengen-Empfehlung. Kein Bezug zu anderen Projekten oder
persönlichen Daten.

## Live-Version

Über GitHub Pages: https://sebnoelle.github.io/weihnachtsbaum-kiosk/

## Auf dem iPad einrichten

1. Link oben in **Safari** öffnen (nicht Chrome)
2. Teilen-Symbol → **„Zum Home-Bildschirm"**
3. App über das neue Symbol starten → läuft im echten Vollbild ohne
   Browser-Oberfläche
4. Für den Kiosk-Schutz zusätzlich **Einstellungen → Bedienungshilfen →
   Zugriffsführung** aktivieren

## Wartungszugang

5x auf die Statuszeile oben tippen öffnet einen PIN-Dialog für einen
harten Neuladen der Seite (PIN ist im Quellcode unter
`KONFIGURATION.wartung.pin` hinterlegt).

## Offene Punkte

Mehrere Preise und Zweig-/Durchmesserangaben in `KONFIGURATION.modelle`
sind noch als `// TODO` markiert und müssen ergänzt werden.
