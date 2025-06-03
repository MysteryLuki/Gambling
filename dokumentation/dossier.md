# Projektbeschreibung: Roulette
## Spielbeschreibung
Das geplante Spiel ist eine digitale Version des klassischen Roulettes, das für Einzelspieler gemacht ist. Die Benutzeroberfläche wird als TUI gestaltet, um eine einfache Interaktion zu ermöglichen. 
### Spielablauf
Der Spieler startet das Programm und wird mit einem Begrüssungsbildschirm empfangen, der ihn auffordert, zu bestätigen, dass er spielen möchte. Nach der Bestätigung wählt der Spieler den Betrag an Spielgeld, den er auf eine bestimmte Farbe setzen möchte, beispielsweise Rot oder Schwarz. 
Sobald der Einsatz platziert ist, beginnt eine animierte Darstellung des Roulette-Rades, die das Drehen und Stoppen des Rades simuliert. Das Ergebnis wird durch eine zufällige Zahl bestimmt. Wenn die gewählte Farbe mit der Zahl übereinstimmt, gewinnt der Spieler und sein Einsatz wird Spielgeld. Der Spieler erhält eine Rückmeldung über seinen aktuellen Kontostand und hat die Möglichkeit, eine neue Runde zu starten oder das Spiel zu beenden. 
Zusätzlich wird ein Highscore System implementiert, das die besten Ergebnisse in einer Datei speichert. Wenn der Spieler einen neuen Highscore erreicht, wird er darüber informiert, und der neue Wert wird in der Datei aktualisiert.
## Testplan
Um die Applikation zu testen, sind folgende Tests geplant:
- **TUI Test**: Überprüfen, ob die Menüs im Terminal richtig angeordnet sind und die Navigation funktioniert
- **Fehlererzeugung**: Ungültige Werte eingeben und schauen, ob das fehlermanagement des Programms funktioniert.
- **Highscore Überprüfung**: Sicherstellen, dass die Highscore-Datei den höchsten Punktestand korrekt speichert und aktualisiert.
- **Mathematische Formeln**: Überprüfen, ob die mathematischen Formeln korrekt sind und keine Fehler enthalten.
- **Stabilitätstest**: Langzeitspieltests durchführen, um sicherzustellen, dass das Programm stabil bleibt und keine Abstürze hat.
## Zeitplan
Der Zeitplan für die Entwicklung des Spiels sieht kontinuierliches Arbeiten am Code bis zum 19. Juni vor. Die Aufgabenverteilung ist gleichmässig, dass jeder 50% der Arbeit macht. 
### Aufgabenverteilung
- **Entwicklung der Benutzeroberfläche**: Eine Person ist verantwortlich für die Gestaltung und Implementierung der TUI, einschliesslich der Menüs und der Anzeige der Spielstände.
- **Spielmechanik**: Eine andere Person kümmert sich um die Logik des Spiels, einschliesslich der Zufallszahlengenerierung und der Berechnung der Gewinne.
- **Highscore-System**: Eine Person wird für die Entwicklung und Integration des Highscore-Systems verantwortlich sein, einschliesslich der Dateioperationen zum Speichern und Abrufen der Punktestände.
- **Optimierung**: Wenn der Hauptteil des Codes geschrieben ist, werden wir beide versuchen den Code für Geschwindigkeit zu optimieren.
- **Dokumentation**: Eine Person wird die gesamte Dokumentation des Projekts erstellen, einschliesslich der Benutzeranleitung und der technischen Spezifikationen.
