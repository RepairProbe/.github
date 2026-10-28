# RepairProbe

**Reparaturinformationen verstehen. Geprüftes von Vermutungen unterscheiden.**

RepairProbe soll Menschen beim Reparieren elektronischer Geräte helfen, verstreute Informationen einzuordnen und zu erkennen, was geprüft wurde und was noch Vermutung ist.

Wer ein Gerät repariert, sucht oft in Anleitungen, Foren, Datenblättern und Videos. Dazu kommen eigene Beobachtungen und Messwerte. RepairProbe untersucht, wie offene Software diese Informationen nachvollziehbar zusammenführen kann. Ein plausibler KI-Vorschlag soll dabei als Vermutung erkennbar bleiben, bis eine passende Überprüfung ihn bestätigt oder widerlegt.

[Projekt kennenlernen →](https://repairprobe.github.io/)

## Ein Beispiel aus der Planung

Ein Radio lässt sich nicht mehr einschalten. Die reparierende Person hält das Gerät, das Problem und sichtbare Beobachtungen mit dem Smartphone fest. RepairProbe soll passende Quellen zuordnen, tatsächliche Messungen von Annahmen trennen und einen begründeten nächsten Prüfschritt erklären.

**Das ist ein geplantes Nutzungsszenario.** Eine solche Smartphone-Anwendung gibt es heute noch nicht. Die Software soll elektrische Fachkenntnis nicht ersetzen und bei gefährlichen oder unbekannten Energiezuständen weitere Schritte blockieren.

## Was vorhanden ist — und was entstehen soll

**Heute:** Im privaten Produktrepository existiert eine kleine Python-Baseline. Sie prüft strukturierte Messdaten, speichert Ereignisse, spielt vorbereitete Beispieldaten reproduzierbar ab und enthält begrenzte Prüfregeln für bestimmte aktive Messmodi. Das belegt Softwareverhalten; Reparaturerfolg, Bildverständnis und KI-Qualität sind damit nicht nachgewiesen.

**Geplant:** Ein frei verfügbarer Prototyp mit einem nachvollziehbaren Reparaturablauf, dokumentierten Quellen, lokaler Falldokumentation und offenem Austauschformat. Der praktische Nutzen soll erst erprobt werden. Ein Förderantrag zum Prototype Fund ist in Vorbereitung und noch nicht eingereicht. Eine Förderung ist nicht bewilligt.

**Langfristig möglich:** Mehr unterstützte Geräte und Beiträge aus der Reparatur-Community. Dafür braucht es weitere Entwicklung und belastbare Erfahrungen aus der Nutzung.

Die erste standardisierte Repair-Café-Rückmeldung ist explorativ (n=1). Sie betont Informationssuche, Gerätezugang und Ersatzteile. Sie bestätigt nicht, dass Reparaturstände häufig verloren gehen, und ist kein Nachweis der Produktwirkung.

## Wer dahintersteht

RepairProbe ist ein unabhängiges Open-Source-Projekt von **Raik Müller**. Sein praktischer Hintergrund liegt im technischen/CNC-Bereich; hinzu kommen Elektronik, Reparaturen, Software und Automatisierung.

Die geplante Software soll ohne eigene RepairProbe-Messhardware und ohne verpflichtenden RepairProbe-Cloudserver auskommen. Lokale Nutzbarkeit, offene Schnittstellen und überprüfbare Regeln gehören zum Zielbild. Eine mögliche externe Recherche oder ein gewählter KI-Dienst kann dennoch eine Netzverbindung benötigen.

## Mehr erfahren oder Rückmeldung geben

- [Website und geplantes Nutzungsszenario](https://repairprobe.github.io/)
- [Was ist Beobachtung, Messung oder Vermutung?](https://repairprobe.github.io/evidenzmodell.html)
- [Projektstand und nächste Entwicklungsschritte](https://repairprobe.github.io/roadmap.html)
- [Vorhandene technische Basis](https://repairprobe.github.io/technical-baseline.html)

Erfahrungen aus der Reparaturpraxis und Hinweise aus Repair-Cafés sind willkommen: **[repairprobe@gmail.com](mailto:repairprobe@gmail.com)**. Eine Rückmeldung oder ein Gespräch bedeutet keine Partnerschaft oder Produktempfehlung.
