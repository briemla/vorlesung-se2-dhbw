# vorlesung-se2-dhbw
## Dozentenreihenfolge
### TINF13 / B1
1. Daniel Lindner
1. Mirko Beine
1. Lars Briem

### TINF13 / B2
1. Lars Briem
1. Daniel Lindner
1. Mirko Beine

### TINF13 / B4
1. Mirko Beine
1. Lars Briem
1. Daniel Lindner

## Vorlesungsinhalt
### TINF13 / B1
####29.09.2015 (lindner)
* Objektorientierte Prinzipien (Folienstand 2010)
	* SOLID
	* GRASP bis Polymorphie

####06.10.2015 (lindner)
* Objektorientierte Prinzipien (Folienstand 2015)
	* GRASP wdh. von Indirektion und Polymorphie
	* GRASP restliche Prinzipien
	* DRY
	* KISS
	* YAGNI
	* Conway's Law
* Refactoring (Folienstand 2010)
	* Einleitung
	* Motivation
	* Einfacher Entwicklungsprozess
	* bis Exkurs Lokalitätsprinzip von Bugs

####13.10.2015 (lindner)
* Refactoring (Folienstand 2010)
	* Ab Exkurs Lokalitätsprinzip von Bugs
	* Code Smells
	* Refactorings
	
####20.10.2015 (beine)
*    Einführung: was ist Design
*    Softwarekomplexität als Kombination von essential complexity, technical complexity und accidential complexity
*    Auswirkungen von Komplexität
*    Big Ball of Mud
*    Warum braucht man Design
*    Übersicht über DDD
*    Grundideen des DDD:
     *    Kollaboration, ubiquitous language
     *    Fachwissen muss sich im Code wiederspiegeln
     *    Fachlogik muss von Nebeneinflüssen isoliert werden
*    Beispiel zu Vorlesungsplan-App ausgearbeitet (Prof, Sekretär, Dozent, Vorlesung, Veranstaltung, Raum, Kurs, Wahlmodul)
*    Erläuterung Knowledge Crunching
*    Strategisches und Taktisches DDD
*    das Domänenmodell als Bindeglied zwischen strategischem DDD und taktischem DDD
*    Value Objects
*    Implementierung von ValueObjects in Java
*    Persisitierung von Value Objects

####27.10.2015 (beine)	
*     Entities, Generierung von Identität
*     Domain Services
*     Aggregates, Transaktionsgrenzen, Lazy Loading, Aggregate Roots
*     Repositories

####03.11.2015 (beine)	
*     Wiederholung Aggregates
*     Factories als allgemeines Konzept, Abstract Factory und Factory Method nicht Teil der Klausur
*     Modules
*     DDD in der Praxis
      *   DDD führt zu Mehraufwand
      *   Mehraufwand muss gerechtfertigt sein
      *   wann lohnt sich DDD / wann nicht
*     Onion Architecture
      *    Klassisches Schichtenmodell
      *    DIP
      *    Umschichtung der Infrastrukturschicht
      *    Domäne als isolierter Kern
      *    Domain Layer
      *    Application Service Layer
      *    Infrastructure Layer

####27.11.2015 (briem)
*   Definition von Bloopern / GUI Bloopern
*   Auswirkungen von Bloopern auf den Benutzer bzw. die Bedienung
*   Ursachen durch die Blooper entstehen
*   Probleme die durch Blooper entstehen
*   Einteilung der Blooper in unterschiedliche Arten
    *   GUI Komponenten
    *   Navigation
    *   Texte
    *   Design und Layout
    *   Interaktion
    *   Management
    *   Antwortverhalten
*   Möglichkeiten zur Vermeidung der Blooper

####04.12.2015 (briem)
#####UI Entwicklung
*   Aufgabenverteilung in der UI Entwicklung
*   Allgmeine Prinzipien zur UI Entwicklung
    *  Benutzer und dessen Ziele sind wichtig
    *  Konzeptionelles Modell
*   Gestalt Prinzipien
*   Gestaltungsrichtlinien

#####Usability Testing
*   Definition von Usability
*   User Centered Design Process
    *   Grobe Übersicht
    *   Benutzerprofile
    *   Iteratives Vorgehen
*   Usability Test
    *   Wichtige Elemente eines Tests
    *   Testarten / Testumgebungen
    *   Testablauf

####11.12.2015 (briem)
#####Usability Testing
*   Experten Review
    *   Ablauf
    *   Evaluationsregeln

#####Paper Prototyping
*   Definition Paper Prototyping
*   Erstellung eines Prototypen
    *   Komponenten
    *   Realismus des Prototyps / der Daten
*   Usability Test mit Paper Prototyping
*   Vergleich Paper Prototyping mit anderen Prototypen
    *   Vor- / Nachteile
    *   Auswahlkriterien für / gegen Paper Prototyping

#####GUI Tests
*    Gründe für GUI Tests
*    Testarten
*    Probleme skriptbasierter / automatischer GUI Tests
*    Vor- / Nachteile einzelner Arten
*    Vor- / Nachteile GUI Tests

### TINF13 / B2
####29.09.2015 (briem)
*   Definition von Bloopern / GUI Bloopern
*   Auswirkungen von Bloopern auf den Benutzer bzw. die Bedienung
*   Ursachen durch die Blooper entstehen
*   Probleme die durch Blooper entstehen
*   Einteilung der Blooper in unterschiedliche Arten
    *   GUI Komponenten
    *   Navigation
    *   Texte
    *   Design und Layout
    *   Interaktion
    *   Management
    *   Antwortverhalten
*   Möglichkeiten zur Vermeidung der Blooper

####06.10.2015 (briem)
#####UI Entwicklung
*   Aufgabenverteilung in der UI Entwicklung
*   Allgmeine Prinzipien zur UI Entwicklung
    *  Benutzer und dessen Ziele sind wichtig
    *  Konzeptionelles Modell
*   Gestalt Prinzipien
*   Gestaltungsrichtlinien

#####Usability Testing
*   Definition von Usability
*   User Centered Design Process
    *   Grobe Übersicht
    *   Benutzerprofile
    *   Iteratives Vorgehen
*   Usability Test
    *   Wichtige Elemente eines Tests
    *   Testarten / Testumgebungen
    *   Testablauf
*   Experten Review
    *   Ablauf
    *   Evaluationsregeln

####13.10.2015 (briem)
#####Paper Prototyping
*   Definition Paper Prototyping
*   Erstellung eines Prototypen
    *   Komponenten
    *   Realismus des Prototyps / der Daten
*   Usability Test mit Paper Prototyping
*   Vergleich Paper Prototyping mit anderen Prototypen
    *   Vor- / Nachteile
    *   Auswahlkriterien für / gegen Paper Prototyping

#####GUI Tests
*    Gründe für GUI Tests
*    Testarten
*    Probleme skriptbasierter / automatischer GUI Tests
*    Vor- / Nachteile einzelner Arten
*    Vor- / Nachteile GUI Tests

####20.10.2015 (lindner)
* Objektorientierte Prinzipien (Folienstand 2015)
	* SOLID
	* GRASP bis Protected Variations

####27.10.2015 (lindner)
* Objektorientierte Prinzipien (Folienstand 2015)
	* GRASP restliche Prinzipien
	* DRY
	* KISS
	* YAGNI
	* Conway's Law
* Refactoring (Folienstand 2010)
	* Einleitung
	* Motivation
	* Einfacher Entwicklungsprozess
    * Auswirkungen von Refactoring
	* bis Exkurs Code Tuning

####05.11.2015 (lindner)
* Refactoring (Folienstand 2010)
    * ab Exkurs Code Tuning
	* Code Smells
	* Spezifische Refactorings
	* Zusatzmaterial: https://schneide.wordpress.com/2013/12/30/from-ugly-to-pretty-three-steps-is-all-it-takes/
	
### TINF13 / B4
####29.09.2015 (beine)
*    Einführung: was ist Design
*    Softwarekomplexität als Kombination von essential complexity, technical complexity und accidential complexity
*    Auswirkungen von Komplexität
*    Big Ball of Mud
*    Warum braucht man Design
*    Übersicht über DDD
*    Grundideen des DDD:
     *    Kollaboration, ubiquitous language
     *    Fachwissen muss sich im Code wiederspiegeln
     *    Fachlogik muss von Nebeneinflüssen isoliert werden
*    Beispiel zu Vorlesungsplan-App ausgearbeitet (Prof, Sekretär, Dozent, Vorlesung, Veranstaltung, Raum, Kurs, Wahlmodul)
*    Erläuterung Knowledge Crunching
*    Strategisches und Taktisches DDD
*    das Domänenmodell als Bindeglied zwischen strategischem DDD und taktischem DDD
*    Value Objects
*    Implementierung von ValueObjects in Java
*    Exkurs: Specifications

####06.10.2015  (beine)
*     Persisitierung von Value Objects
*     Entities, Generierung von Identität
*     Domain Services
*     Aggregates, Transaktionsgrenzen, Lazy Loading, Aggregate Roots
*     Repositories

####05.11.2015  (beine)
*     Wiederholung Aggregates
*     Factories als allgemeines Konzept, Abstract Factory und Factory Method nicht Teil der Klausur
*     Modules
*     DDD in der Praxis
      *   DDD führt zu Mehraufwand
      *   Mehraufwand muss gerechtfertigt sein
      *   wann lohnt sich DDD / wann nicht
*     Onion Architecture
      *    Klassisches Schichtenmodell
      *    DIP
      *    Umschichtung der Infrastrukturschicht
      *    Domäne als isolierter Kern
      *    Domain Layer
      *    Application Service Layer
      *    Infrastructure Layer

####19.10.2015 (briem)
*   Definition von Bloopern / GUI Bloopern
*   Auswirkungen von Bloopern auf den Benutzer bzw. die Bedienung
*   Ursachen durch die Blooper entstehen
*   Probleme die durch Blooper entstehen
*   Einteilung der Blooper in unterschiedliche Arten
    *   GUI Komponenten
    *   Navigation
    *   Texte
    *   Design und Layout
    *   Interaktion
    *   Management
*   Möglichkeiten zur Vermeidung der Blooper

####26.10.2015 (briem)
* Letzte Blooper Kategorie
    *   Antwortverhalten
*   Möglichkeiten zur Vermeidung der Blooper

#####UI Entwicklung
*   Aufgabenverteilung in der UI Entwicklung
*   Allgmeine Prinzipien zur UI Entwicklung
    *  Benutzer und dessen Ziele sind wichtig
    *  Konzeptionelles Modell
*   Gestalt Prinzipien
*   Gestaltungsrichtlinien

#####Usability Testing
*   Definition von Usability
*   User Centered Design Process
    *   Grobe Übersicht
    *   Benutzerprofile
    *   Iteratives Vorgehen
*   Usability Test
    *   Wichtige Elemente eines Tests
    *   Testarten / Testumgebungen
    *   Testablauf

####02.11.2015 (briem)
#####Usability Testing
*   Experten Review
    *   Ablauf
    *   Evaluationsregeln

#####Paper Prototyping
*   Definition Paper Prototyping
*   Erstellung eines Prototypen
    *   Komponenten
    *   Realismus des Prototyps / der Daten
*   Usability Test mit Paper Prototyping
*   Vergleich Paper Prototyping mit anderen Prototypen
    *   Vor- / Nachteile
    *   Auswahlkriterien für / gegen Paper Prototyping

#####GUI Tests
*    Gründe für GUI Tests
*    Testarten
*    Probleme skriptbasierter / automatischer GUI Tests
*    Vor- / Nachteile einzelner Arten
*    Vor- / Nachteile GUI Tests

####10.11.2015 (lindner)
* Programming Principles
	* Einleitung
	* SOLID
	* GRASP bis Mitte Kopplung
	* Zusatzmaterial: Buch zu Interfaces https://pragprog.com/book/kpiod/interface-oriented-design
	* Zusatzmaterial: Buch zu Interfaces und Ports and Adapters http://www.growing-object-oriented-software.com/

####18.11.2015 (lindner)
* Programming Principles
	* GRASP bis Ende
	* DRY
	* KISS
	* YAGNI
	* Conway's Law

####25.11.2015 (lindner)
* Refactoring Refactoring (Folienstand 2010)
	* Einleitung
	* Motivation
	* Einfacher Entwicklungsprozess
    * Auswirkungen von Refactoring
    * Exkurs Code Tuning
	* Code Smells
	* Spezifische Refactorings
	* Zusatzmaterial: https://schneide.wordpress.com/2013/12/30/from-ugly-to-pretty-three-steps-is-all-it-takes/
