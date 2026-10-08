# WEHA Bedachungen – Website-Entwurf

V3: bildreicher und kompakter, statischer Website-Auftritt in Unternehmensrot (#d71100), Anthrazit und Weiß. Original-Logo, großes Original-Dachfoto im Hero, Serifentypografie, fünf direkte Projekte auf der Startseite, sechs bebilderte Leistungsbereiche, kompakte Abschnitte und Projektgalerien, große Menüansicht und flächiger Kontaktbereich. Die Neugestaltung umfasst sämtliche Unterseiten.

## Vorschau und Bearbeitung

Startseite: `index.html`. Lokal: `python -m http.server 8000 --directory .`.
Inhalte und Templates stehen in `build.py`, Projektdaten in `projects.json`. Neu erzeugen: `python build.py`.
Styles und Interaktionen: `assets/style.css` und `assets/main.js`.
Das fertige Hauptverzeichnis kann unverändert auf einem statischen Host oder im Hauptverzeichnis eines GitHub-Pages-Repositories bereitgestellt werden. Alle internen Links und Assets sind relativ.

## Umfang

36 HTML-Seiten: Startseite, Über uns, Leistungen, sechs Leistungsdetailseiten, Bildergalerie, 19 einzelne Projektgalerien, Kontakt, Kontaktformular, Partner, Stellenanzeigen, Impressum, Datenschutz, 404.
Die bestehenden HTML-Routen einschließlich der Projektgalerien bleiben erhalten. Das bisher verlinkte `formular.php` antwortete beim Abruf mit 404. Ein funktionsfähiger E-Mail-Vorbereitungsdialog ersetzt es auf `formular.html` und der Kontaktseite.

## Funktionen

Responsive Navigation mit Tastatur- und Escape-Bedienung, Projektfilter und Suche, native modale Bildansicht mit Vor/Zurück und Pfeiltasten, aufklappbare Stellenangebote, reduzierte Bewegung bei entsprechender Systemeinstellung.
Das Kontaktformular erstellt ausschließlich einen E-Mail-Link. Es gibt keine automatische Zustellung und kein Formular-Backend. Der Besucher prüft und sendet seine Nachricht in seinem E-Mail-Programm.
Keine externen Schriften, Tracking-Werkzeuge oder eingebetteten Karten. Karten und Herstellerseiten öffnen erst nach Klick. Die Präsentationsversion besitzt `noindex,nofollow` und eine sperrende robots.txt.

## Quellen und Fakten

Originalauftritt: https://www.weha-gmbh.de/ – erfasst am 08.10.2026.
Bestehende Seiten: index.html, ueberuns.html, leistungen.html, bildergalerie.html, kontakt.html, partner.html, stellenanzeigen.html, impressum.html, datenschutz.html.
Gründung 1994, Familienbetrieb Wegert, Radwanger Str. 3 in Dinkelsbühl, Kontakt- und Registerdaten wurden dem bisherigen Auftritt entnommen. Die unsichere aktuelle Mitarbeiterzahl wurde nicht als neue Kennzahl übernommen. Zimmererarbeiten werden ausdrücklich der kooperierenden Zimmerei zugeordnet. Die 30-Jahre-Veröffentlichung wird als Meilenstein 2024 eingeordnet.
Stellen und Partner folgen den bestehenden Veröffentlichungen. Details und Aktualität sind vor einem offiziellen Livegang mit dem Betrieb abzustimmen.

## Bildnachweise

19 vollständige Projektgalerien mit insgesamt 115 Bildern, dazu drei Unternehmensfotos und das Original-Logo, lokal übernommen und als WebP optimiert. Keine generierten Bilder oder erfundenen Referenzen. Das Hero-Foto stammt aus Projekt Zirndorf (Bild 4).
Die Projektmetadaten in `projects.json` dokumentieren die jeweiligen Originalquellen. Die ursprüngliche Website nennt Dominic Wegert als Bildeigentümer, soweit nicht anders vermerkt. Bilder des alten Amtsgerichts: BFF O. Heindl. Bildnachweise sind auch im Impressum und Datenschutz des Entwurfs enthalten. Freigabe der Verwendung mit den Rechteinhabern vor dem offiziellen Livegang abstimmen.

## Prüfungen und Freigabe

JavaScript-Syntax, lokale Seiten- und Bildverweise, Bilddateien und HTML-Grundstruktur geprüft. Visuelle Browser-QA ist in dieser Umgebung nicht verfügbar und bleibt ausstehend.
Impressum und Datenschutz sind gekennzeichnete Entwurfsseiten. Vor offiziellem Livegang Betreiber- und Hostingdaten, rechtliche Texte, Stellenverfügbarkeit und tatsächliche Kontaktzustellung abstimmen. Der Entwurf ist eine Präsentation, nicht der freigegebene offizielle Unternehmensauftritt.
