# Woche 01

Willkommen im Modul "Ausgewählte Kapitel der Gesundheitsinformatik"! In der ersten Woche reden wir über den allgemeinen Ablauf des Moduls - diese Informationen finden Sie hier verschriftlicht.

## Thema

In diesem Modul beschäftigen wir uns mit Next Generation Sequencing und der Auswertung der dabei entstehenden Daten, wobei die Implementation der Algorithmen in Python stattfindet. Kurz zusammengefasst: In den ersten Wochen werden wir uns auf der fachlichen Seite mit den molekularbiologischen Grundlagen auseinandersetzen und auf der Informatik-Seite Python üben. Danach schauen wir uns in der Vorlesung unterschiedliche Analysen von Genomdaten an und implementieren in der Übung die entsprechenden Algorithmen/Tools. Details zu den genauen Themen, die wir uns anschauen, gibt es in der nächsten Woche.

## Allgemeiner Ablauf

Jede Woche findet eine Online-Vorlesung statt. In dieser können im ersten Teil Fragen zum Inahlt der Übungsaufgaben gestellt werden, im zweiten Teil werden fachliche Hintergründe (Molekularbiologie, Algorithmen der Bioinformatik) vorgestellt und gemeinsam diskutiert.

Zudem gibt es jede Woche Übungsaufgaben. Diese werden jeweils am Dienstag (erstmals am 13.4.2021) freigeschaltet und sind zum darauffolgenden Dienstag 02:00 (also in der Nacht von Montag zu Dienstag) spätestens abzugeben. Diese Hausaufgaben beziehen sich jeweils auf die am Freitag davor besprochenen Inhalte. Somit müssten Sie eigentlich das nötige Wissen für die Bearbeitung der Aufgaben haben, sollten aber Fragen auftauchen, haben Sie nochmal vor der Abgabefrist eine Online-Veranstaltung, in der Sie Ihre Fragen loswerden können.

Zusätzlich zu den Online-Vorlesungen gibt es im Moodle-Kurs ein Forum. Stellen Sie sehr gerne Ihre Fragen dort, dann können nämlich alle von den Antworten profitieren!

Es finden in diesem Semester keine Übungen als Online-Veranstaltung statt - leider ist die Sorte Interaktion, von der Übungen profitieren, online nicht möglich. Nutzen Sie bitte stattdessen das Forum oder kontaktieren Sie mich per Mail, falls Sie bei der Bearbeitung der Hausaufgaben Fragen haten!

## Übungsaufgaben auf github classroom

Um den Umgang mit git zu üben, arbeiten wir in diesem Modul mit github classroom. In Moodle wird jede Woche die Übungsaufgabe als ein Einladungs-Link zu github classroom veröffentlicht. Klicken Sie auf diesen Link **während Sie bei github eingeloggt sind**, so wird für Sie ein individuelles, privates Repository angelegt. Beim ersten Klick auf den Link müssen Sie aus der Liste der Teilnehmenden auswählen, wer Sie sind, damit Ihr github-Account mit Ihrem Moodle-Account verknüpft wird. 

Das Repository, das für die Aufgabe angelegt wird, können Sie dann lokal klonen (beispielsweise über die [PyCharm-IDE](https://www.jetbrains.com/pycharm/), für die Sie bei Anmeldung über Ihre HTW-Mailadresse kostenlos die kommerzielle Lizenz bekommen, über den Button "Get from VCS" beim Erstellen eines neuen Projektes).

In den ersten Wochen, in denen wir Python üben, finden Sie drei Dateien in den Aufgaben-Repositories: skript.py, aufgaben.py und test_aufgaben.py. In skript.py sind die Grundlagen von Python aufeinander aufbauend erklärt, zwischendurch finden Sie Referenzen auf Aufgaben in der Form von ```# --- Aufgabe <Nummer>: <Thema> (siehe aufgaben.py) ---```. Einen entsprechend benannten Abschnitt mit vordefinierten Methodensignaturen und Aufgabenbeschreibungen finden Sie in aufgaben.py, wo Sie die entsprechenden Implementationen vornehmen sollen. In test_aufgaben.py finden Sie für jede Aufgabe einen Test, der auch automatisch ausgeführt wird, wenn Sie Ihren Code in das Reposiroty pushen (in IDEA über die Menüpunkte "Git->Commit" und dann "Git->Push"). Sie können die Tests entsprechend auch lokal ausführen, um zu sehen, ob Ihr Code funktioniert (in IDEA über Klick auf die grünen Pfeile neben den Methodensignaturen der Tests). Die Ergebnisse der Tests und entsprechend Ihre Punktzahl können Sie in github im Reiter "Actions" sehen.

Bitte denken Sie daran, Ihre Lösungen rechtzeitig vor Ablauf der jeweiligen Frist zu pushen!

## Prüfung und Zulassungsvoraussetzungen

Für jede der wöchentlichen Hausaufgaben gibt es maximal 10 Punkte. Um zur Prüfung zugelassen zu werden, müssen Sie 75% der Punkte über alle Übungen hinweg erreichen. 

Die Prüfung wird dann in Form einer erweiterten Hausaufgabe stattfinden - Sie bekommen ein umfangreicheres Tool zu programmieren, das von der Art her den Übungsaufgaben ähnelt und ebenfalls über github classroom abgegeben wird.

## Mitarbeit am Skript

Wie Sie sehen können, steht auch das Skript in github zur Verfügung. Wenn Sie Verbesserungsvorschläge haben oder Fehler finden, können Sie entweder einen issue aufmachen oder das Repository forken, die Verbesserung einführen, und einen pull request in dem Skript-Repository aufmachen. Damit üben Sie nicht nur die Arbeit mit github sondern tragen auch zu einer Verbesserung des Skriptes für die nächsten Semester bei. Entsprechend können Sie auf Ihre finale Zensur bis zu 5% Bonus bekommen: Für jeden pull request für das Skript, den ich annehme, bekommen Sie 2.5% Bonus, bis zu einem Maximum von insgesamt 5%.

## Begleitmaterialien

Zusätzlich zum Skript gibt es einige Lightboard-Videos, die als Begleitmaterial zur Verfügung gestellt werden. Diese werden, so vorhanden, in dem Skript verlinkt (und eventuell nachgetragen - es sind noch nicht alle gedreht, und aufgrund der sich verschärfenden Corona-Situation kann ich nicht garantieren, dass alle rechtzeitig fertig werden). In dem ersten Video geht es darum, [was wir in dieser Woche bezüglich NGS allgemein besprechen](https://mediathek.htw-berlin.de/video/Next-Generation-DNA-Sequencing/09488d7886091c17fc9c259cca9ea534). Dazu direkt eine Bemerkung: Bei den Längen habe ich mich ein wenig verhaspelt, die korrekten Genomlängen sind:

 * Viren: 2 Kb - 1 Mb
 * Bakterien: 500 Kb - 12 Mb
 * Tiere: 10 Mb - 130 Gb
 * Pflanzen: 60 Mb - 130 Gb


