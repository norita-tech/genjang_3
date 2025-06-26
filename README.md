## Projektarbeit 
Du hast eine Anstellung als Data Engineer (-in) beim Mischkonzern ‚Müller AG‘ gefunden 
und bist in der Abteilung externes IT-Consulting angestellt. Als erstes Projekt wird dir ein 
Auftrag von Extern zugewiesen. Es geht um den Zoo in Pirmasens. Der Zoo besteht seit 
36 Jahren. Im Zuge einer umfassenden Modernisierung soll der Betrieb des Zoos 
zukünftig u.a. it-gestützt ablaufen. Ein integriertes IT-System gibt es jedoch noch nicht. 
Und hier kommst du bzgl. Themen aus dem Bereich des Data Engineering ins Spiel. 

Du sollst nach Rücksprache mit dem Geschäftsführer des Zoos (Ansprechpartner: Herr 
Teske) die folgenden Schritte durchführen: 
1. Erstelle ein vollständiges Datenmodell (ERM) der zukünftigen operativen 
Datenbank. M:N Beziehungen sind aufgelöst darzustellen. Die Primärschlüssel, 
Fremdschlüssel und Kardinalitäten (1:1, 1:N, N:1, …) sind ins Datenmodell 
einzutragen. Die Relationen sind zu beschriften (Notation wie bei Lösung zur 
Aufgabe Baustoffgroßhandlung).
2. Setzte das Datenmodell aus 1. in eine relationale Datenbank um inklusive 
Dokumentation (Data Dictionary). Lese die Referenzdaten (siehe Datei 
‚Wertebereiche.txt‘) vom Kunden in die Datenbank ein.
3. Die Geschäftsleitung des Pirmasenser Zoos interessiert sich ebenfalls für 
Business Intelligence. Konkret geht es um ein Data Warehouse. Welches Data 
Warehouse Schema empfiehlst Du hier? Warum? Erstelle ein entsprechendes 
Datenmodell inkl. passender Data Warehouse IT-Architektur. 
4. Eine hohe Datenqualität ist in diesem Vorhaben sehr wichtig. Erstelle ein Konzept, 
wie der Datenbestand fortlaufend bearbeitet werden kann und die Datenqualität 
auf ein >97% Level kommt. 
5. Für die Projektergebnisse ist eine Präsentation zu erstellen und beim Kunden 
zu präsentieren.

# Anmerkung: 
Zur Umsetzung der oben genannten Punkte sind Gespräche beim 
Kunden (Herr Teske) zwingend notwendig. Im Rahmen der Anforderungserhebung 
muss kein Lastenheft erstellt werden. Die Gespräche sind jedoch zu dokumentieren.

## Our team started by understanding the project and organising a meeting with Mr Teske as seen below
Wir sind ein vierköpfiges Team, das in der Unterabteilung Data Engineering für ein Beratungsunternehmen arbeitet. Mischkonzern, Weber AG". Ein Projekt wurde von unserem Kunden zur Kenntnis gebracht; Primasens für einen Job, der ihren Zoo betrifft. Der Zoo besteht seit 36 Jahren. Im Zuge einer umfassenden Modernisierung soll der Betrieb des Zoos zukünftig u.a. IT-gestützt ablaufen. Ein integriertes IT-System gibt es jedoch noch nicht. Aus diesem Grund sucht der Kunde unsere Expertise bei der Erstellung seines Operative Data System und Data Warehouse.
Nach eingehender Prüfung der Projektdetails und Wünsche unseres Kunden entdeckten wir die Komplexität der Angelegenheit und beschlossen, ein Treffen mit ihrem Ansprechpartner Herrn Teske zu buchen, um mehr über ihre Entitäten und Erwartungen zu sprechen. In diesem Zusammenhang haben wir einige Fragen für mehr Klarheit gestellt. (Siehe das vorgelegte Fragebogen ). 
Bevor wir mit Herrn Teske sprachen, stellten wir sicher, dass einige Best Practices befolgt wurden.
•	Halten Sie unsere Informationen zentralisiert. Wir haben unsere Kommunikation zentralisiert und rationalisiert. Alle unsere Notizen, Statusaktualisierungen, Dateien, Entscheidungen und mehr sollten an einem Ort gespeichert werden, damit der Kunde finden kann, was er braucht, ohne Zeit damit zu verschwenden, in endlosen E-Mail-Threads oder Kommentaren danach zu graben. 
•	Einen Ansprechpartner in jeder Phase haben, um den Informationsfluss zu erleichtern
•	Festlegung klarer Erwartungen und Lieferungen
•	Verstehen, was der Kunde wirklich will, indem er manchmal wiederholt Fragen stellt.

# From our conversation with Mr Teske, we discovered the following:
•	Alles Analoge wurde bisher mit Stift und Papier abgebaut und ihr Ziel ist es nun, diese Methode fallen zu lassen und mit einem vollständig integrierten IT-System fortzufahren.
•	Der Zoo hat etwa 70 Mitarbeiter und 50 registrierte Tier Artzs
•	Die geschaeftsprozesse muessen aktuell abgebildet werden auf taeglicher basis
•	Die datenbestaende muessen 1:1 mit der Realitaet mithalten, daher 97% Datenqualitaet gefordert, also ein kleiner zeitlicher versatz ist okay, beispiel lieferung von futter, aber lagerbestand und tierzustand muss immer 100% aktuell
•	Daten werden automatisch abfotografiert und digital gespeichert, dann die eingabe der jeweiligen daten wird nur die daten betreffen, die aktuell sind.
•	Mitarbeitern brauchen schulung fuer die umstellung auf das neue system und dementsprechend einfach soll es in der behandlung sein.

# In the Project, we 
- Created an ERM
- data-dictionary
- IT erchitecture
- data_model_star_schema
- Data_model_data_vault
- Data quality.
