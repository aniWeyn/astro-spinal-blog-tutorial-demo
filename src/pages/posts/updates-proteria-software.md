---
layout: "../../layouts/MarkdownPostLayout.astro"
title: Updates Proteria Software
pubDate: 2024-01-18T15:27
description: 
author: Anja Füger
image: 
---

11\.04.24:

* Möglichkeit zur Erstellung einer monatlichen Anschreibeliste / Monatsbericht

* Möglichkeit zum Download des Logbuchs zum Nachrichtentausch

* Vorlage definiert jetzt auch welche Datengruppen beim Erstellen einer neuen Anmeldung geöffnet/geschlossen sein sollen

* Behoben: App-Crash beim Drucken auf Grund aktivierter Popup-Blocker

* Datengruppen PV/AV/Zolllager auf Positionsebenen können jetzt durch einfachen Button \"bereinigt\" werden, auch wenn man nicht (mehr) das entsprechende Verfahren gewählt hat

* csv Berichte / Exports wurden erweitert mit Daten: Ausführer-Name, Ausführer-EORI, Anmelder-EORI

* Behoben: Backend-Timeouts der Anmeldedatenführten ab und zu zu Fehlern bei Abfrage von Kontakten oder Artikeln

* 

19\.01.2024

* Versenden von Nachrichten zum Warenverbleib jetzt uneingeschränkt möglich (eigene Plausibilitätsprüfung derselben wird innerhalb weniger Tage verfügbar sein)

* «Neue Anmeldung» links im Hauptmenü erstellt nun die Anmeldung auf Basis der Standardvorlage. Ist keine Vorlage vorhanden oder keine als „Standard“ markiert, wird eine leere Anmeldung erstellt.

* Übersicht der Vorlagen zeigt nun nur Benutzer-eigene Vorlagen (nicht mehr alle der gesamte Firma)

* Beim Senden von ergänzenden Anmeldungen oder eines „Nachtrags zur Anmeldung“ wird nun der Status „letzte Nachricht“ in der Übersicht direkt, sofort aktualisiert.

* Behoben: Löschen von Unterlagen zeigte hängende „Laden..“-Icon

* Behoben: Fehlermeldung beim Versuch ABD/AV aus alte ATLAS-2.4 Vorgänge zu öffnen. Solche Vorgänge haben oft die PDF (noch) im alten System, daher kann es sein, dass die pdf im neuen System nicht verfügbar ist.

* Behoben: Fehlende Darstellung von Ausgangszollstelle und E-Mail-Adressen in der Ansicht einer Anmeldung im „Nur-Lesen“-Modus

* Neu: Vorlage kopieren

* Verbesserung: Lange Datenfelder in der Übersicht werden jetzt gekürzt dargetellt

* Verbesserung: Im Kontaktregister (bei Eingabe, Änderung) kann das Land jetzt auch nach Ländername (nicht nur Code) gesucht werden

* Verbesserung: Eigene Farbdarstellung (orange) von Vorgängene die Fehler-Antworten erhalten haben

* Verbesserung: Warenposition-&gt;Ursprungsbundesland wird jetzt automatisch auf 99 gesetzt, wenn Warenposition-&gt;Ursprungsland ungleich Deutschland ist

* Behoben: „Warenposition-&gt;Ergänzende Masseinheit bleibt auf allen Positionen rot markiert, wenn eine Position einen Plausibilitätsfehler erhält

* Verbesserung: Das Verhalten und Design von Drop-Down Eingabefeldern die über TAB aktivert werden, wurde leicht verbessert