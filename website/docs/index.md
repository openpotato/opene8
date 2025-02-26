# Einführung

OpenE8 macht es sich zur Aufgabe, den Datenaustausch von Verwaltungsdaten im Bildungsbereich zu standardisieren, für alle Schularten aller Bundesländer. Wir stehen damit noch ganz am Anfang und wollen mit dieser Webseite zunächst die wesentlichen Ziele formulieren:

+ **Ziel 1**: Kuratieren und Bereitstellen von Schlüsselverzeichnissen bzw. Code-Listen, speziell für die Schulverwaltung. Wir nutzen dazu den [OpenCodeList](https://openpotato.github.io/opencodelist/de/)-Standard und stellen die Daten mit Hilfe des [CodeListHub-Projektes](https://www.codelisthub.org/de/) zur Verfügung.

+ **Ziel 2**: Open Source-Spezifikation von aufeinander aufbauenden Komponenten zur Repräsentation von Entitäten in der Schulverwaltung (z.B. Lehrer:innen, Schüler:innen, Eltern, Organisationen, Schullaufbahn, Ausbildungsdaten, Noten, Abschlüsse, Zeugnisse etc.). Wir nutzen hierzu [JSON](https://www.json.org/) als Repräsentationsformat.

+ **Ziel 3**: Open Source-Spezifikation einer [RESTful-API](https://www.openpotato.org/de/blog/2025/02/25/restful-api-erklaert/) zum Synchronisieren von Daten zwischen zwei oder mehreren Systemen.

    + Generieren und Einspielen von Snapshots für folgende Anwendungsfälle:
	
	    + Migration von kompletten Datenbeständen zwischen zwei Systemen
		+ Erstellen von (verschlüsselten) Datenarchiven zur digitalen Archivierung
		
	+ Generieren und Einspielen von Änderungen für folgende Anwendungsfälle:
	
	    + Live-Synchronisierung oder asynchroner Abgleich von Daten zwischen mehreren Systemen
	    + Support für Patching, einem Ansatz zur Datenminimierung durch das Synchronisieren von lediglich geänderten Daten (inklusive Support für das Löschen von Daten)

Der Namensbestandteil E8 leitet sich aus dem englischen Begriff für Bildung - *Education* - ab: Die Zahl 8 repräsentiert die Anzahl der Zeichen nach dem E.

## Aktueller Status

Wie bereits erwähnt, ist OpenE8 noch ganz in der Entwicklungsphase. Aktuell stehen einige wenige Code-Listen auf [CodeListHub](https://explorer.codelisthub.org/de/) bereit, die vom [OpenT8](https://openpotato.github.io/opent8/)-Format genutzt werden. Über [Feedback](community.md) jeglicher Art würden wir uns sehr freuen.