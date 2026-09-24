# Hirtenweg Lab

Willkommen im Hirtenweg Lab, einem inoffiziellen GitHub-Bereich für technische Projekte, Experimente, Werkzeuge und Ideen rund um die Schule Hirtenweg.

Hier werden digitale Projekte entwickelt, getestet, dokumentiert und geteilt, die den Schulalltag, das Lernen, die Barrierefreiheit, die Infrastruktur und kreative Experimente unterstützen.

Vorerst sind die Repositories auf *privat* gestellt. Bei Interesse zu einem Repository: Gerne melden.

## Projektehttps://github.com/towade?tab=repositories

### Schulalltag und Informationsbildschirme

| Repository | Beschreibung | Technik |
|---|---|---|
| `schulboard` | Webanwendung für digitale Schulboards mit Spaltenansicht, PDF-Vorschauen und einer Verwaltung per Drag-and-drop | Node.js, Express, EJS |
| `busabfahrtsmonitor` | Anzeige und Verwaltung der täglichen Busabfahrten | PHP 8.3, nginx, MySQL 8.4, Docker Compose |
| `motto` | „Motto der Woche“: wöchentlich zufällig gezogenes Motto für einen Infobildschirm, optional mit Foto und Vertonung um das Kollegium zu motivieren, mit eigenem Adminbereich | PHP 8.3, nginx, MySQL 8.4, Docker Compose |

### Lernen und Spiel

| Repository | Beschreibung | Technik |
|---|---|---|
| `notrufsim` | Kindgerechte Web-App zum Üben des Notrufs 112 mit einer KI-gestützten Leitstelle, vollständig selbst gehostet | Next.js, TypeScript, Ollama, Whisper, Piper TTS |
| `henriette-game` | „Henriette Hirtenweg – Roll & Rool!“: Browser-Spiel im Stil des bekannten Dino-Spiels | Node.js, Express, HTML/JavaScript |

### Energie und Monitoring

| Repository | Beschreibung | Technik |
|---|---|---|
| `solartankstelle` | Monitoring der Photovoltaikanlage mit Home Assistant und GoodWe-Anbindung, CSV-Export-Dienst und Kiosk-Dashboard zur Einbindung in IServ | Python, Home Assistant |

Die meisten Repositories sind derzeit privat und nur für ausgewählte Mitwirkende zugänglich. Weitere Projekte kommen nach und nach hinzu.

## Gemeinsame Grundsätze

- **Selbst gehostet:** Die Anwendungen laufen auf eigener Infrastruktur, KI-Funktionen nach Möglichkeit mit lokalen Modellen statt Cloud-Diensten.
- **Container-basiert:** Die Bereitstellung erfolgt in der Regel über Docker Compose. Die Anwendungen selbst bleiben möglichst unabhängig vom Hosting.
- **Konfiguration getrennt vom Code:** Zugangsdaten und lokale Einstellungen liegen nie im Repository. Mitgeliefert werden ausschließlich Vorlagen wie `.env.example` oder `config.example.php`.
- **Laufzeitdaten bleiben draußen:** Hochgeladene Dateien, Datenbankinhalte und andere Betriebsdaten der Schule sind per `.gitignore` ausgeschlossen.
- **Dokumentiert:** Jedes Repository enthält eine README mit Einrichtung, Konfiguration und Betrieb.

## Über diese Organisation

Das Hirtenweg Lab ist nicht der offizielle GitHub-Auftritt der Schule Hirtenweg. Es handelt sich um einen unabhängig gepflegten Projektbereich für technische und pädagogische Arbeiten im Umfeld der Schule.

Offizielle Informationen zur Schule Hirtenweg sollten immer über die offiziellen Kommunikationswege und die Website der Schule bezogen werden.

## Sicherheit und Datenschutz

Repositories dürfen insbesondere folgende Inhalte nicht enthalten:

- Passwörter, API-Schlüssel, Tokens oder andere Zugangsdaten
- personenbezogene Daten von Schüler:innen, Mitarbeitenden oder Eltern
- vertrauliche Schuldokumente
- interne Infrastrukturdetails, die ein Sicherheitsrisiko darstellen könnten

Sensible Informationen gehören in entsprechend geschützte Systeme und nicht in ein Git-Repository. Git vergisst nichts, auch keine versehentlich eingecheckten Passwörter.

## Mitwirken

Beiträge, Vorschläge, Fehlermeldungen und Verbesserungen sind willkommen, sofern das jeweilige Repository dies vorsieht. Je nach Projekt kann die Zusammenarbeit über Issues, Pull Requests, Discussions oder direkt mit den Repository-Mitgliedern erfolgen.

## Lizenz

Die Lizenzierung wird für jedes Repository einzeln festgelegt. Sofern nicht ausdrücklich anders angegeben, gilt keine allgemeine Lizenz für sämtliche Projekte innerhalb des Hirtenweg Lab.

## Weitere Ressourcen

Eine Sammlung interessanter externer Projekte und Werkzeuge findest du hier:

👉 [Open Source für Schule](open-source-fuer-schule.md)

---

**Hirtenweg Lab** ·
*Build. Test. Learn. Improve.*

Inoffizieller technischer Projektbereich rund um die Schule Hirtenweg.
