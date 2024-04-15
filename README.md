# ToDoListe
# Sehr geehrte Damen und Herren !!! Heute möchten wir unsere Arbeit presentieren. Es geht hier um das Thema: " ToDoListe". Diese Präsentation wird im Namen von Anastasiia Khrypko, Baltasar Garcia Davila und Sabir Suleyman gehalten. Selbstverständlich können Sie am Ende unseres Vortrags noch Fragen stellen, wir beantworten diese gerne. Lassen Sie uns jeden dieser JavaScript-Dateien genauer betrachten:
# index.js:
# Diese Datei ist der Einstiegspunkt der Anwendung.
# Sie importiert benötigte Funktionen und Objekte aus anderen Dateien.
# Dann fragt sie den Benutzer nach seinem Namen, formatiert ihn und gibt eine Begrüßung aus.
# Anschließend wird die Funktion toDoList() aufgerufen, die dem Benutzer ermöglicht, eine Aktion aus einer Liste auszuwählen, und je nach Benutzerwahl die entsprechende Funktion aufruft.
# addNewTask.js:
# Diese Datei enthält die Funktion addNewTask(), die eine neue Aufgabe zur Liste hinzufügt.
# Der Benutzer wird aufgefordert, eine Beschreibung der Aufgabe und einen Fälligkeitsdatum einzugeben.
# Wenn der Benutzer eine Beschreibung eingibt, wird die Aufgabe zum Array tasks hinzugefügt, sonst wird eine Fehlermeldung ausgegeben.
# Die Funktion verwendet auch die Funktion dateChoice(), die den Benutzer nach dem Fälligkeitsdatum der Aufgabe fragt.
# tasks.js:
# In dieser Datei werden die Arrays tasks und completedTasks definiert, die alle Aufgaben bzw. abgeschlossenen Aufgaben speichern.
# Diese Arrays werden exportiert und können von anderen Modulen verwendet werden, um auf die Aufgabendaten zuzugreifen.
# functions.js:
# Diese Datei enthält Funktionen zum Bearbeiten von Aufgaben: Anzeigen aller Aufgaben, Markieren einer Aufgabe als erledigt und Löschen einer Aufgabe aus der Liste.
# Sie verwenden das Array tasks aus tasks.js, um auf die Aufgabendaten zuzugreifen.
# Nachdem eine Aufgabe abgeschlossen oder gelöscht wurde, können die Funktionen auch das Array completedTasks in tasks.js aktualisieren.
# quotes.js:
# In dieser Datei wird das Array quotes definiert und die Funktion randomQuote() implementiert, die ein zufälliges Zitat und seinen Autor in der Konsole ausgibt.
# Die Funktion wird verwendet, um nach Abschluss der Arbeit mit der Anwendung eine zusätzliche Nachricht anzuzeigen.
# Die Interaktion zwischen den Dateien erfolgt durch Importieren und Exportieren von Daten und Funktionen. Jede Datei erfüllt ihre Aufgabe im Rahmen der Gesamtlogik der Anwendung, die es dem Benutzer ermöglicht, die Aufgabenliste zu verwalten und Inspiration aus zufälligen Zitaten zu erhalten. Ich erteile das Wort meiner Kollegin 