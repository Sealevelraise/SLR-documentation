# Inhalt

*   [User Profiles](#user-profiles)
*   [Epics](#epics)
*   [User Stories](#user-stories)
*   [Offene Fragen](#offene-fragen)
*   [Außerhalb des Projektumfangs](#außerhalb-des-projektumfangs)

* * *

## User Profiles
* * *

#### Ute

Alle Personen, die Spenden für ein Projekt erhalten möchten und dafür ein Projekt registrieren, verifizieren und zur Abstimmung aufstellen wollen.

#### Peter

Alle Personen, die spenden möchten und für Projekte abstimmen wollen.

#### DAO

Die DAO besteht aus allen Spendern (Peters) und ist eine dezentrale autonome Organisation, die kontrolliert welche Projekte zur Abstimmung kommen, wie die Abstimmung abläuft und die Spendengelder verteilt werden.

## Epics
* * *

| **#** | **Epic** | **Beschreibung** |
| --- | --- | --- |
| 1   | Website besuchen | Die Website hat eine Landing Page und es kann eine Spenderrolle ausgewählt werden. |
| 2   | Spenden | Alle Prozesse, um eine Spende abgeben zu können. |
| 3   | Spendenquittung | Das Ausstellen und Verschicken der Spendenquittung. |
| 4   | Voten | Alle Prozesse, um für ein Projekt abstimmen zu können. |
| 5   | Projektkür | Alle Prozesse, um die Spendensumme entsprechend Abstimmung auszugeben. |
| 6   | Projekt einreichen | Small-State-Check und Eingabe der Projektinformationen. |
| 7   | Projekt überprüfen und anlegen | Alle Prozesse, um ein Projekt in den Abstimmungsprozess aufzunehmen. |
| 8   | Projektaccount anlegen | Alle Prozesse zur Erstellung eines eigenen Projektaccounts für den Empfang von Spendengeldern. |

## User Stories
* * *

| **#** | **User Story Titel** | **User Story** | **Acceptance Criteria** |
| --- | --- | --- | --- |
| **1.01** | Startseite (Spenden/Projekt anlegen) | Als Peter oder Ute möchte ich eine Startseite angezeigt bekommen, um weiter fortzufahren. | 1.  Die Seite ist aufrufbar.<br>    <br>2.  Beim Aufrufen der Seite soll das Wählen der Rolle offensichtlich einsehbar sein. |
| **1.02** | Spenderrolle auswählen | Als Peter oder Ute möchte ich meine Rolle auswählen können, um zur entsprechenden Seite weitergeleitet zu werden. | 1.  Die Rollen sollen offensichtlich mit den beiden Funktionen “Spender sein” und “Spender suchen” verbunden sein.<br>    <br>2.  Nach Klick auf einen Button werde ich auf die jeweilige Seite weitergeleitet. |
| **2.01** | Wallet anlegen | Als Peter möchte ich die Schritte erklärt bekommen, wie ich mein Wallet einrichten und hinterlegen kann. | to be defined |
| **2.02** | Spendenbutton klicken | Als Peter möchte ich meine Spendendaten eingeben und auf einen Button klicken, um meine Spende abzugeben. | 1.  Es ist ein Formular zur Eingabe aller nötigen Informationen vorhanden.<br>    <br>2.  Es ist ein Button zum Absenden der Informationen vorhanden.<br>    <br>3.  Wenn der Button gedrückt wird, wird auf der Seite eine Erfolgsmeldung für meine Spende angezeigt. |
| **2.03** | Geld transferieren | Als Peter möchte ich, dass mein Geld transferiert wird und ich eine Meldung bekomme, um meine Spende zu absolvieren. | 1.  Der zu spendende Betrag wird vom Spender-Wallet abgebucht und auf den Smart Contract gebucht.<br>    <br>2.  Es erscheint eine Meldung, über die erfolgreiche Transaktion. |
| **2.04** | Mitglied der DAO werden | Als Peter möchte ich Mitglied der DAO werden, um an Abstimmungen teilhaben zu können. | 1.  Über anstehende Abstimmungen in der DAO wird informiert.<br>    <br>2.  Es ist möglich, in der DAO abzustimmen. |
| **2.05** | Token erhalten | Als Peter möchte ich einen Token erhalten, um meine Stimme abgeben zu können. | 1.  Nach erfolgreicher Spende wird ein Token gutgeschrieben.<br>    <br>2.  Der Token ermöglicht die Abstimmung in der DAO. |
| **3.01** | Spendenquittung ausstellen | Als DAO möchte ich eine Spendenquittung ausstellen, um die Spende steuerrechtlich anzuerkennen und Spender zu motivieren. | 1.  Es wird eine Spendenquittung erstellt. |
| **3.02** | Spendenquittung verschicken | Als DAO möchte ich eine Spendenquittung verschicken, um sie Peter zur Verfügung zu stellen. | 1.  Die Spendenquittung wird an Spender verschickt. |
| **4.01** | Projektübersicht aller aktiven Projekte | Als Peter möchte ich alle Projekte angezeigt bekommen, um ein Projekt für meine Stimme auswählen zu können. | 1.  Nach der Transaktion der Spende werden alle verfügbaren Projekte mit Projekttitel, Bild, Beschreibungstext und Spendenziel angezeigt. |
| **4.02** | Stimmenabgabe | Als Peter möchte ich ein Projekt auswählen können, um meine Stimme für ein Projekt abzugeben. | 1.  Mit Klick auf “Projekt auswählen” öffnet sich ein Dropdown mit allen Projekten.<br>    <br>2.  Mit Auswahl eines Projekts schließt sich das Dropdown.<br>    <br>3.  Mit Klick auf “Absenden” erhalte ich eine Benachrichtigung über abgegebene Stimmen.<br>    <br>4.  Beim ersten Klick auf “Absenden” erscheint eine Melung mit dem Projektnamen, welches ausgewählt wurde und der Abfrage: "Sind Sie sicher?"    |
| **4.03** | Spenden ohne Voten | Als Peter möchte ich ein Häkchen setzen können, um mich beim Voting zu enthalten bzw. der DAO zu vertrauen. | 1.  Neben dem Dropdown-Menü gibt es ein Häckchen “ohne Stimme spenden”.<br>    <br>2.  Nach Klick auf “Absenden” mit ausgewähltem Häckchen erhalte ich eine Benachrichtigung über abgegebene Stimmen. |
| **4.04** | Stimmenübersicht anschauen | Als Peter möchte ich eine Übersicht der bisherigen Stimmen pro Projekt angezeigt bekommen, um zu wissen ob mein favorisiertes Projekt gewinnen könnte. | to be defined |
| **5.01** | Vierteljährliche Benachrichtigung kommt rein | Als Peter möchte ich eine Benachrichtigung erhalten, wenn eine neue vierteljährliche Spendenperiode beginnt, um zu sehen welches Projekt gewonnen hat und zu wissen, dass eine neue Periode mit neuen Projekten beginnt. | 1.  Mit Beginn der neuen Spendenperiode erhalte ich eine Benachrichtigung mit allen notwendigen Informationen darüber. |
| **5.02** | Projekt mit den meisten Stimmen auswählen | Als Peter möchte ich wissen nach welchem Prinzip das Gewinner-Projekt bestimmt wird, um meine Stimme dementsprechend abgeben zu können. | 1.  Nach Ende der Abstimmungsperiode wird das Projekt mit den meisten Stimmen in der abgelaufenen Spendenperiode per “Winner takes it all” als Gewinner bestimmt. |
| **5.03** | Geld an Projekt transferieren | Als DAO möchte ich das gespendete Geld transferieren, wenn das Gewinner-Projekt gewählt wurde, um die Spendengelder auszuzahlen. | 1.  Der Betrag auf dem Smart Contract zum Ende der Spendenperiode wird auf das Wallet der Person mit dem Projekt mit den meisten Stimmen ausgezahlt. |
| **5.04** | Erfolgreiches Projekt announcen | Als Peter oder Ute möchte ich eine Benachrichtigung erhalten, welches Projekt die Abstimmung gewonnen hat. | 1.  Zum Ende der Spendenperiode erhalten alle Teilnehmer (egal welcher Rolle) eine Benachrichtigung über das Abstimmungsergebnis. |
| **5.05** | Neues Spenden-Vierteljahr starten | Als DAO möchte ich nach Ende einer Spendenperiode eine neue Spendenperiode mit den bis dahin angemeldeten Projekten starten, um neue Spendengelder zu sammeln. | 1.  Nach Ende einer Spendenperiode wird eine neue Spendenperiode gestartet.<br>    <br>2.  Es werden alle bis dahin eingetragenen Projekte |
| **6.01** | Smallstateliste | Als Ute möchte ich aus einer Liste aller Smallstates meinen Smallstate auswählen, um ein Projekt anlegen zu können. | 1.  Nach Wählen der Rolle “Spender suchen” wird zur Wahl des Smallstates aufgefordert.<br>    <br>2.  Mit Klick auf “Smallstate auswählen” wird eine durchsuchbare Dropdown-Liste mit allen Smallstates angezeigt.<br>    <br>3.  Ein Smallstate wird ausgewählt und nach Klick auf “Weiter” werde ich auf die Seite “Projektinformationen eingeben” weitergeleitet. |
| **6.02** | Eingabe der Projektinformationen | Als Ute möchte ich meine Projektinformationen eingeben, um ein Projekt anlegen zu können. | 1.  Es wird ein Formular mit Eingabefeldern zu allen nötigen Informationen angezeigt.<br>    <br>2.  Wenn nicht alle Felder gefüllt sind, wird bei Klick auf “Ok” zur Befüllung aller Felder aufgefordert.<br>    <br>3.  Nach Klick auf “Ok” mit allen befüllten Feldern, werden Informationen an Backend übertragen und über das weitere Vorgehen informiert. |
| **7.01** | Projekt registrieren | Als DAO möchte ich ein Projekt mit seinen Informationen registrieren, um es verifizieren zu können. | 1.  Es wird ein neues Projekt angelegt und es werden alle Informationen gespeichert. |
| **7.02** | Ute verifizieren | Als DAO möchte ich Ute verifizieren können, um Missbrauch zu vermeiden. | to be defined |
| **7.03** | Projekt verifizieren | Als DAO möchte ich ein neues Projekt verifizieren können, um Missbrauch zu vermeiden. | to be defined |
| **7.04** | Abstimmung über Annahme eines Projekts | Als DAO möchte ich über die Annahme eines Projekts abstimmen, um dessen Eignung sicherzustellen. | 1.  Es wird vor Start einer neuen Spendenperiode darüber abgestimmt welche Projekte in die Abstimmung mit aufgenommen werden. |
| **7.05** | Projekt-Keys (Adresse) generieren | Als DAO möchte ich für ein neues Projekt einen Key bzw. eine Adresse generieren, um Stimmensammlung und Spendentransfer zu ermöglichen. | 1.  Mit Erstellung eines neuen Projekts wird ein Public Key als Adresse für Stimmensammlung und Spendentransfer generiert. |
| **7.06** | Nachricht an Ute senden | Als DAO möchte ich eine Nachricht an Ute senden, um ihr mitzuteilen, ob und mit welcher Adresse ihr Projekt für die nächste Abstimmung hinterlegt wurde. | 1.  Die erstellende Person wird laufend über den Annahme-Prozess ihres Projekts informiert. |
| **8.01** | Projekt-Account annehmen | Als Ute möchte ich einen Projekt-Account annehmen, um diesen verwalten zu können. | 1.  Der Projekt-Ersteller hat die Möglichkeit, den Projekt-Account mit seinem eigenen Account zu verknüpfen.<br>    <br>2. to be defined  |
| **8.02** | Wallet anlegen | Als Ute möchte ich die Schritte erklärt bekommen, wie ich mein Wallet einrichten und hinterlegen kann. | to be defined |
| **8.03** | Wallet hinterlegen | Als Ute möchte ich ein Wallet hinterlegen, um Spenden erhalten zu können. | 1.  Es kann ein Wallet hinterlegt werden, um Spendengelder aus der Projektadresse auf die private Wallet zu übertragen. |
| **8.04** | Darstellung des eigenen Spendenimpacts | Als Ute möchte ich meinen eigenen Spendenimpact darstellen, um transparent für Stimmen zu werben. | 1.  Beschreibungstext und Fotos können zu einem Projekt hinzugefügt, entfernt oder geändert werden.<br>    <br>2.  Mit Klick auf “Speichern” werden die Änderungen gespeichert. |

## Offene Fragen
* * *

| **Frage** | **Antwort** | **Antwortdatum** |
| --- | --- | --- |
| Was passiert mit den Projekten, die nicht gewonnen haben? Werden Sie automatisch in die nächste Spendenperiode wieder aufgenommen? |     |     |
| Darf ich nur in der Spendenperiode abstimmen, in der ich auch gespendet habe? |     |     |
| Muss ich, um in einer Spendenperiode abzustimmen, auch in dieser gespendet haben? Oder habe ich mit einer einmaligen Spende in jeder Spendenperiode das Recht abzustimmen (unabhängig ob ich gespendet habe = Token sind ewig gültig)? |     |     |
| Können alle die Projekt-Übersicht einsehen, oder nur die bereits abgestimmt haben? |     |     |
| Wie funktioniert die Verifikation von Ute? |     |     |
| Wie funktioniert die Verifikation von Projekten? |     |     |
| Wie läuft das mit Private Key des Projekts (Story 8.01)? |     |     |

## Außerhalb des Projektumfangs
* * *

*   Bezahlung mit Kryptowährung in Small States siehe [Bezahlung mit Kryptowährung in Small States](https://htw-berlin-bui.atlassian.net/wiki/spaces/SEAL/pages/5931013)
    

*   Definition Small States und Prozess der Einreichung von Projekten