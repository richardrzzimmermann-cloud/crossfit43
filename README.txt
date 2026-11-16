CrossFit 43 Offline PWA

Inhalt:
- index.html
- app.js
- styles.css
- manifest.webmanifest
- sw.js
- icon.svg

Wichtig: Service Worker funktionieren nur ueber HTTPS oder localhost, nicht durch direktes Oeffnen der index.html als file:// Datei.
Zum Testen am PC im entpackten Ordner: python3 -m http.server 8080
Fuer Installation auf Android den gesamten Ordner auf einen HTTPS-Webspace laden, einmal in Chrome oeffnen und 'App installieren' bzw. 'Zum Startbildschirm hinzufuegen' waehlen.
