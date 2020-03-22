# DUS_Ratsinformationssystem_json_zu_Excel

Lädt Informationen zu allen augenblicklich im Ratsinformationssystem (RIS) der Stadt Düsseldorf online befindlichen "papers" herunter,
inkl. download-links

Beispiel-Code erfordert REQUEST Package

Es werden die json-Antworten runtergeladen für die für wesentlich erachteten "keys":
- "organizaton"
- "meeting"
- "person"
- "paper"

Im weiteren Verlauf werden die Details NUR der Papers abgerufen und ein data frame / eine Tabelle mit den wichtigsten
Informationen geschaffen.

Diese Tabelle erlaubt eine schnelle Übersicht über die z.Z. im RIS-DUS online befindlichen Dokumente. Im Augenblick handelt es sich
meist um PDFs mit Anträgen oder Beschlussvorlagen für Rat oder Bezirksvertretung.

Die Tabelle wird letztlich auch als Excel-Datei gespeichert. Diese enthält die aktiven download-Links zu den Dokumenten.
