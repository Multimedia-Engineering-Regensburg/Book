# Multimedia Engieering am Lehrstuhl für Medieninformatik

Der Kurs *Multimedia Engineering* schließt an die Veranstaltungen *Einführung in die Objektorientierte Programmierung* (OOP) sowie *Einführung in die Anwendungsentwicklung* (Android) an. Sie vertiefen hier Ihre erworbenen Kenntnisse im Bereich der Programmierung und Softwareentwicklung. Dazu lernen Sie mit dem *Browser* eine neue Anwendungsplattform kennen und erwerben erste Erfahrungen im Bereich der Implementierung und Strukturierung von Javascript-Anwendungen. Javascript und der *Browser* dienen dabei als Mittel, um Ihnen zentrale Inhalte und Methoden der Softwaretechnik (engl. [Software engineering](https://en.wikipedia.org/wiki/Software_engineering)) näher zu bringen. Im Kurs setzen Sie sich mit der bewussten Gestaltung von [Architektur](https://en.wikipedia.org/wiki/Software_architecture) und [Design](https://en.wikipedia.org/wiki/Software_design) von Software auseinander. Sie lernen die Qualität von Software-Implementierungen, insbesondere deren Quellcodes einzuschätzen und verwenden Methoden und Werkzeuge um diese zu steigern bzw. zu sichern. Vorhandene Kenntnisse im Bereich der Versionsverwaltung werden am praktischen Beispiel von `git` vertieft. Zusätzlich lernen Sie, diese Werkzeuge und Methoden im Rahmen der kollaborativen Softwareentwicklung sinnvoll einzusetzen. 

Ohne grundlegende Programmierkenntnisse können Sie den Kurs nicht erfolgreich besuchen. Die grundlegenden Strukturen der eingesetzten Programmiersprache Javascript werden nicht oder nur teilweise im Kurs behandelt. Große Teile der Sprache müssen Sie sich daher selbständig aneignen. Der Übergang von Java zu Javascript ist relativ einfach, sollten Sie sich in den Bereichen der objektorientierten oder *Event*-basierten Programmierung aber noch unsicher sein, werden Sie zwangsweise auf Probleme stoßen. Zentrale Inhalte aus den vorangegangenen Kursen, die in MME vorausgesetzt werden sind z.B. das Modellieren von Anwendungen mit Hilfe von Objekten, Verarbeitung von Eingabeereignissen, grundlegende Entwurfsmuster wie *Model View Controller* oder das *Observer Pattern*, Datenpersistenz und asynchrone Datenverarbeitung.

## Ziele

Nach dem erfolgreichen Abschluss des Kurses sollten Sie Ihre im universitären Umfeld erworbenen Fähigkeiten zur Implementierung von Anwendungssoftware ausgebaut und verbessert haben und neue Methoden und Techniken für die Ausgestaltung des Entwicklungsprozesses kennen gelernt haben. Grundsätzlich gilt dabei für viele der Themenfelder: **Softwaretechnik kann in der Regel nur gelernt, nicht aber gelehrt werden.** Die im Kurs behandelten Themen können nur durch ihre praktische Anwendung verinnerlicht und verstanden werden. Die verfügbare Zeit, Aufbau und Struktur des Kurses und vor allem der begrenzte Kenntnisstand des Dozenten machen es nicht möglich, Sie innerhalb eines Semesters zu einem Experten auf den thematisierten Feldern zu machen. Sehen Sie die Veranstaltung daher als einen Baustein in einem kontinuierlichen Lernprozess, der Sie zu einem besseren Programmierer bzw. einer besseren Programmiererin macht. Neben den in Modulkatalog und Vorlesungsverzeichnis definierten Lern- und Kompetenzzielen sollten Sie daher auch versuchen, Ihre persönlichen Ziele für den Kurs zu definieren. Schätzen Sie Ihre eigenen Programmier- und Entwicklungskenntnisse ein und versuchen Sie, diese im Laufe des Semesters zu verbessern. Dabei ist es egal, mit wie viel Vorwissen Sie in den Kurs hineingehen. Sie werden genügend Gelegenheiten finden, Ihre Fähigkeiten zu reflektieren und auszubauen. Im Rahmen einiger Übungen und der anschließenden Projekte werden Sie kollaborativ an der Entwicklung gemeinsamer Anwendungen arbeiten - Nutzen Sie daher im Vorfeld unbedingt die selbstständige Vorbereitung auf die einzelnen Sitzungen sowie die Übungsaufgaben, um an Ihren individuellen Fähigkeiten zu arbeiten ohne sich auf das Tempo oder die Vorgehensweise von anderen einstellen zu müssen. 

## Herangehensweise

Der Semesterteil des Kurses teilt sich in via Live-Stream durchgeführte Online-Sitzungen und ein eigenständiges Selbststudium auf, das bestmöglichst durch [Lerngruppen](./study-groups) unterstützt wird. In der ersten Semesterhälfte erhalten Sie zu Beginn jeder Woche eine aufbereitete Lerneinheit, dern Inhalte Sie sich im Selbststudium eigenständig erarbeiten. Die Anwendung der so erworbenen, theoretischen Grundlagen werden in einer begeleitenden Live-Veranstaltung demonstriert. In diesem Semester erfolgt die Demonstration über einen Live-Stream auf der Plattform [Twitch.tv](https://twitch.tv/alexanderbazo). Dabei haben Sie Gelegenheit, über einen Chat-Kanal Feedback zu geben und Fragen zu stellen. Alle Sitzungen stehen im Anschluss als Videoaufzeichung bereit. Einen detaillierten Semesterplan finden Sie [hier](../../).

## Selbststudium und Übungsaufgaben

Zu jeder zweiten inhaltlichen Sitzung wird es eine sehr kleine Übungsaufgabe geben, die Sie innerhalb einer Woche bearbeiten und abgeben müssen. **Für Studierende, die nach neuer Studienordnung studieren (ab WS 2017/18) gelten die Übungsaufgaben als verpflichtende Studienleistungen (Vgl. [Modulbeschreibung](https://www.uni-regensburg.de/studium/modulbeschreibungen/medien/ba/medieninformatik-ba-ws1718.pdf)).** Bitte versuchen Sie, eine eigenständige und selbsterarbeitete Lösung einzureichen. Auf dem Weg dahin können Sie sich gerne innerhalb Ihrer Lerngruppe unterstützten. Auch wir stehen Ihnen bei Fragen oder Problemen gerne zur Verfügung. Mehr Informationen dazu finden Sie auf [dieser Seite](../../../Aufgaben).

Beginnen Sie möglichst früh damit, Ihre Arbeit mit Hilfe von `git` zu dokumentieren und berücksichtigen Sie konsequent die Hinweise des eingesetzten *Linting*-Tools. Das gilt sowohl für die Vorbereitung auf die Sitzungen als auch für die Implementierungen der Übungsaufgaben. 

Versuchen Sie, bei allen Entwicklungsaufgaben eine angemessene Lösungsstrategie zu verwenden:

1. **Planen Sie Ihre Herangehensweise**. Stellen Sie sicher, dass Sie Aufgaben- und Problemstellung verstanden haben. Versuchen Sie den groben Aufbau der Anwendung zu skizzieren: Welche Aufgaben müssen innerhalb der Anwendung erledigt werden? Welche Komponenten (Module, Objekte) sind dafür notwendig und wie werden die Aufgaben auf diese aufgeteilt? Wie lassen sich diese Komponenten strukturieren? Wie und mit Hilfe welcher Schnittstellen kommunizieren die Komponenten miteinander? Erstellen Sie eine grobe Skizze der Architektur sowie der Benutzeroberfläche. Überlegen Sie sich, mit Hilfe welcher *Muster* die Struktur, das Verhalten oder die Kooperation der Komponenten implementiert werden können.

2. **Nehmen Sie sich Zeit.** Solange Sie die Abgabefrist einhalten spielt es keine Rolle, ob Sie 10, 100 oder 500 Zeilen Code pro Tag produzieren. Investieren Sie genügend Aufwand in die Planung, um mögliche Probleme schon vor der Implementierung zu erkennen und unnötige Neustrukturierung Ihrer Anwendung zu vermeiden. Teilen Sie sich Ihre Zeit so ein, dass Sie möglichst wenige Aufgaben pro Sitzung bearbeiten müssen.

3. **Denken Sie Feature-orientiert.** Nehmen Sie sich stets eine kleinteilige Aufgabe vor, die zu einer messbaren Veränderung der Anwendung führt. Arbeiten Sie nicht an mehreren Stellen oder Komponenten gleichzeitig. Schließen Sie eine Aufgabe vollständig ab, bevor Sie mit der nächsten beginnen. 

4. **Testen Sie Ihre Lösung.** Kontrollieren Sie nach der Fertigstellung eines Features, ob sich Ihre Lösung fehlerfrei in die Anwendung integriert. Überlegen Sie sich zu Anfang die wichtigsten Szenarien, die die Verwendung Ihrer Anwendung durch den Nutzer beschreiben und testen Sie stets, ob die von den Änderungen betroffenen Abschnitte des Programms weiterhin verwendbar sind.

5. **Überarbeiten Sie Ihren Code.** Quellcode erreicht in den seltensten Fällen einen perfekten Zustand. Scheuen Sie sich nicht davor, bereits funktionierende Teile der Anwendung [umzuschreiben](https://en.wikipedia.org/wiki/Code_refactoring), um eine höhere Codequalität, bessere Performanz oder geringere Fehleranfälligkeit zu erreichen. Lesen Sie regelmäßig den von Ihnen geschriebenen Code. Halten Sie dabei jedes mal nach Verbesserungsmöglichkeiten Ausschau (Vgl. [The Boy Scout Rule](http://proquest.tech.safaribooksonline.de/book/software-engineering-and-development/agile-development/9780136083238/chapter-1-clean-code/ch1lev1sec6_html?uicode=regensburg)).

6. **Dokumentieren Sie Ihr Vorgehen.** Verwenden Sie Versionskontrolle um den Fortschritt der Implementierung festzuhalten. Verwenden Sie Kommentare im Code um komplexe Vorgänge und Lösungen zu beschreiben. Beschreiben Sie im Zweifelsfall, warum Sie eine bestimmte Lösung gewählt haben. Beschreiben Sie vor allem solche Stellen im Code, die als Schnittstelle zu anderen Komponenten dienen (für andere Entwickler aber auch für Sie selbst).

## Projekte

Im Anschluss an den Semesterkurs fertigen Sie in Kleingruppen ein eigenes Entwicklungsprojekt an. Die thematische Ausrichtung können Sie dabei selbst wählen. Die Implementierung erfolgt als Webanwendung und auf der Basis der im Kurs vermittelten Techniken. Neben der konkreten Umsetzung der Anwendung weisen Sie im Rahmen des Projekts auch nach, dass Sie in der Lage sind, kollaborativ an der Implementierung einer Anwendung zu arbeiten, dabei notwendige Schritte und Maßnahmen zur Sicherstellung einer ausreichenden Code-Qualität anzuwenden und Ihr Vorgehen und Ergebnis sauber zu dokumentieren. 

Konkretes Ziel der Projekte ist die Bereitstellung einer *Browser*-basierten Anwendung, die einen konkret definierbaren Mehrwert für eine beliebige Nutzergruppe bietet. Die Anforderungen an diese Software werden im Vorfeld informell erhoben und mit Hilfe von *User Stories* dokumentiert. Sie verwenden ein auf [github](https://github.com) bereit gestelltes *Repository* zur Pflege Ihrer *code base* sowie zur Dokumentation des Projektfortschritts.  

## Transfer

Die erworbenen Fähigkeiten können Sie im Anschluss ganz konkret in den weiteren Veranstaltungen des Bachelor-Studiums sowie des anschließenden Master-Studiengangs verwenden. Von der Verbesserung Ihrer grundlegenden Programmier- und Entwicklungskenntnisse sollten Sie in allen Kursen profitieren, die die praktische Umsetzung eines Softwareprojektes erfordern. Im Besonderen sollten Sie versuchen, die im Rahmen des Abschlussprojekts erworbenen Kenntnisse auf dem Gebiet der kollaborativen Softwareentwicklung auf die Planung, Dokumentation und Umsetzung zukünftiger Gruppenprojekte zu übertragen. Konkrete Kenntnisse auf dem Gebiet der Implementierung von Webanwendungen werden Ihnen dort von Nutze sein, wo Sie schnell Prototypen oder Anwendungen für einen größeren Benutzerkreis bereitstellen müssen. Dies können Projekte im Praxisseminar oder eigene Vorhaben im Rahmen von z.B. Ihrer Abschlussarbeit sein. 

## Lernfragen

Unter einigen Lektionen finden Sie Lernfragen im *Multiple Choice*-Format. In der Regel beziehen sich diese auf die theoretischen Inhalte des jeweiligen Textes und sollen Ihnen helfen, die zentralen Aussagen der Lektion zu wiederholen und den Lernfortschritt zu testen. Denken Sie daran, dass die Bearbeitung der praktischen Übungsaufgaben, die sich ebenfalls am Ende einer Lektion befinden, von größerer Bedeutung für ihren persönlichen Lernfortschritt sind.