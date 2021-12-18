# News Monitoring System

*Für den Kurs nehmen wir eine fiktive Firma.*

Wir sind eine kleine Firma, welche im Schweizer Markt im Bereich News-Monitoring personalisierte Dienstleistungen anbieten möchte. Wir wissen das internationale Firmen sowie Behörden oft den Bedarf nach individualisiertem Mediamonitoring haben.

##  Wir möchten folgende Dienstleistungen anbieten:
- Diensteistungen abgestimmt auf persönlichen Informationsbedarf:
  - Handverlesene Meldungen der grossen Agenturen zB AP, AFP, dpa, APA, sda, XINHUA, Interfax, Al Jazeera.
  - Täglicher One-pager, welche die wichtigesten Meldungen der letzten 24h zusammenfassen.
  - 24/7/365 Alerting (via persönlichem Telefon).
- Nachrichten werden als Email oder in maschinenlesbarer Form auf API's übermittelt.
- Analyse-Plattform: Zugriff auf die gesamte Datenbasis aus 100er Quellen mit analytischen Funktionen.
- Automatische Übersetzung der Meldungen in Englische Sprache.

Für den Beginn unserer Geschäftstätigkeit konzentrieren wir uns auf Printmedien.

## Funktinale Anforderungen:
- Der Analyst kann die Nachrichten ausgewählter Agenturen triagieren;
- Der Analyst kann sein Sprachpreferenz konfigurieren um zu entscheiden, welche Sprachen im Original und welche in Englischer Übersetzung angezeigt werden;
- Der Analyst kann Nachrichten dem Kunden zustellen;
- Der Analyst Listen (Merklisten) mit Meldungen um zB die täglichen One-pager vorzubereiten;
- Der Poweruser kann Agentur-Quellen konfigurieren;
- Der Poweruser kann Empfänger (Email, Empfangssystem-Schnittstellen) konfigurieren;
- Das System kann Nachrichten an Empfangssysteme senden (REST und sFTP);
- Der Analyst erstellt die One-pager ausserhalb der Software in Microsoft Word und versendet diese via Email direkt an den Kunden;
- Der Nutzer kann Nachrichten drucken.
- Die Analytics-Plattform bietet Zugriff auf alle Nachrichten-Artikel;
  - Der Analyst kann Nachrichten mittels Filtern suchen;
  - Der Analyst kann Filter speichern;
  - Der Analyst kann Dashboards erstellen;
  - Die Nachrichten werden in Originalsprache und Englisch angezeigt;

## Randbedingung
- Die Software wird auf einer eigenen Infrastruktur betrieben;

## Bestehende Anbieter im Markt und weitere Quellen
- Argus: https://www.argusdatainsights.ch/de/
- Factiva: https://www.dowjones.com/professional/factiva/
- Silobreaker: https://www.silobreaker.com/
- Metlwater: https://www.meltwater.com/de
- Angebot von sda für Nachrichten im Textformat: https://www.keystone-sda.ch/web/guest/text 
  - Spezifikation: https://www.keystone-sda.ch/documents/20143/0/NewsML-Guidelines_1.2b.pdf/648d1a23-f088-5405-804a-8a38be233ca8?t=1582905020719

## Fragen zur Beantwortung als Vorbereitung für den nächsten Kurstag
- [ ] Was sind Nachrichtenagenturen?
- [ ] Was ist AP, AFP, dpa, APA, sda?
- [ ] Für wen / welche Firmen könnte ein News-Monitoring System von nutzen sein?
- [ ] Welche Elemente sind im Kontext für die Software "NewsMon"? Organisationen, Systeme, Aktoren, Geräte.
- [ ] Welche UseCases erledigen die Actoren an der Software?

<!--
ADR
- Analyse-Komponente von Silobreaker
- Triage selber schreiben
--> 
