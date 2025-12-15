# Version - 1.21.002
## Allgemein - Handling
### Inaktive Benutzer
Erweiterung des Benutzers um das Feld "Inaktiv".\
Sobald der Benutzer inaktiv ist, wird dieser in der Terminplanung ausgeblendet.
## Datenaustausch
### Import von Ansprechpartnern
Die Ansprechpartner werden nun täglich aus ABAS importiert.\
Es werden nur neue & geänderte Datensätze verarbeitet.
### Import von Hardware-Artikeln
Die Hardware-Artikel werden nun täglich aus ABAS importiert.\
Es werden nur die systemrelevanten Hardware-Artikel übergeben.\
> [!NOTE]
> Diese stehen nun auch im Servicebericht unter Material zur Verfügung.
### Import von Dienstleistungsartikeln
Die Dienstleistungsartikel werden nun täglich aus ABAS importiert.\
Es werden alle systemrelevanten Dienstleistungsartikel übergeben.
> [!IMPORTANT]
> Kundenspezifische Dienstleistungsartikel werden nicht in der Standard-Auswahl angezeigt.\
> Diese stehen nur durch importierte Aufträge zur Verfügung.
## Terminplanung
### Neue Sonderzeit: Vertriebsunterstützung
Mit der neuen Sonderzeit ist es nun möglich Vertriebsunterstützung im Kalender zu kennzeichnen.
### Neue Fehlzeit: Dienstreise (Übernachtung)
Mit der neuen Fehlzeit ist es nun möglich mehrtägige Dienstreisen mit Übernachtung im Kalender darzustellen.
### Umbenennung der Fehlzeit "Fokustag"
Die Fehlzeit Fokustag wurde auf die Bezeichnung "Fokuszeit" umbenannt.
### Erweiterung der Auswahl-Liste für alle Standorte
Die Auwahl-Liste in der Terminplanung wurde auf alle Standorte erweitert.
### Eigener Standort als Standard-Auswahl
Beim Laden der Terminplanung wird der eigene Standort in der Standort-Auswahl als standart vordefiniert und ausgewählt.
### Fokus bei Kundenauswahl
Bei der Kundenauswahl im Termin wird der Fokus automatisch in das Suchfeld gesetzt, sodass man direkt die Suche durch Eingabe starten kann.
## Rechteänderungen
### Systemberater/Systemtechniker
- Kalender | Fehlzeit - Ansicht (Ab ISGUS GmbH)
- Kalender | Sonderzeit - Ansicht (Ab ISGUS GmbH)
- Kalender | Termine - Ansicht (Ab ISGUS GmbH)
### Technischer Leiter/Teamleiter
- Kalender | Fehlzeit - Ansicht (Ab ISGUS GmbH)
- Kalender | Sonderzeit - Ansicht (Ab ISGUS GmbH)
- Kalender | Termine - Ansicht (Ab ISGUS GmbH)
### Administration / Planer
- Kalender | Fehlzeit - Ansicht (Ab ISGUS GmbH)
- Kalender | Sonderzeit - Ansicht (Ab ISGUS GmbH)
- Kalender | Termine - Ansicht (Ab ISGUS GmbH)
### Vertriebsbeauftragte
- Kalender | Fehlzeit - Ansicht (Ab ISGUS GmbH)
- Kalender | Sonderzeit - Ansicht (Ab ISGUS GmbH)
- Kalender | Termine - Ansicht (Ab ISGUS GmbH)
### Niederlassungsleitung
- Kalender | Fehlzeit - Ansicht (Ab ISGUS GmbH)
- Kalender | Sonderzeit - Ansicht (Ab ISGUS GmbH)
- Kalender | Termine - Ansicht (Ab ISGUS GmbH)
## Fehlerbehebungen
- #2 Im Arbeitsbereich Benutzerverwaltung war das Anlegen von neuen Benutzer nicht möglich, beim Speichervorgang ist ein Fehler aufgetreten.
