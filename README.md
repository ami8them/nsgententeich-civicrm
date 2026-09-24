# NSG Ententeich Civicrm
CiviCRM Config für ein Netzwerk dass ein Bürgerbegehren durchführt zum Schutz eines Naturschutzgebietes: civicrm.wa-wie.de (zuletzt aufgerufen 24.09.26).

**Beschreibung:**
Ähnlich wie beim Haustürwahlkampf wird für die eigenen Zwecke geworben durch das Klingeln an Haustüren, Gespräche führen und Flyer einwerfen. Damit dies richtig getracked werden kann und Menschen nicht analog in Karten markieren müssen, wo sie bereits waren, bieten CiviCRM & Drupal eine einfache Website Lösung. Aktive bekommen einen Log-In Zugang um Haustüren zu ergänzen, bei denen bereits Aktivität passiert ist. Sie können zudem auf einer Karte einsehen, ob an einer Straße schon Aktive Unterschriften gesammelt haben, oder dies noch offen ist. Zusätzlich werden von CiviCRM Tools genutzt zur Mailinglistenverwaltung und -versand sowie Veranstaltungsankündigungen.

**Warum Git?**
 Dieses Repository ist dazu gedacht, dass Leute die Config benutzen können, sollten sie ähnliche Vorhaben durchführen wollen. Zudem bietet es eine gute Möglichkeit der Dokumentation und eine extra Speicherung neben den Server-Backups.

## Extensions & Modules

**Genutzte CiviCRM Tools / Extensions**
- CiviMail: Versand von Mail-Newsletter
- CiviEvent: Veranstaltungs-Kalender (intern und extern)
- Calender: Ansicht der Veranstaltungen
- Geocoder: Zum Geocoden der Haustür-Adressen (check & Ansicht Karte)
- Weitere: AdminUI, AuthX, Civi-Import, CKEditor4, Formbuilder, SearchKit, Login Destination

**Genutzte Drupal Modules**
- CiviCRM: Core, Entity, Entity Leaflet, Theme, Webform
- Geofield: Geofield, Leaflet, Leaflet Views
- Mails: SMTP Authentication Support
- Weitere:Calendar View, Webform

## Account-Zuweisung

| Rolle      | machine name           | Wer?  |
| ------------- |-------------| -----|
| anonymous user  | anonymous | öffentlich |
| authenticated user   | authenticated      |   Klingler*innen |
| coordinator | klinglerin      |    Koordinator*innen |
| content editor | content_editor      |    Hauptverantwortliche Aktion |
| administrator | administrator     |    Admins |

## Conributers
Wir danken der Drupal und CiviCRM Community für die tolle Möglichkeit, unser Netzwerk durch ein CRM Tool zu unterstützen.

LiGrü, Aaron & Ami
