# home-codeingStandardsRefactoring-afrizberg

# Definition Refactoring
Die Verständlichkeit des Codes. 

## Vor- und Nachteile von Refactoring
### Vorteile
- Man kann es besser lesen
- Man kann es besser wiederverwerten
- Man kann es besser verstehen

### Nachteile

- Es können neue Fehler passieren die man gar nicht bemerkt.
- Es dauert länger und am Ende besteht kein wesentlichen Unterschied in der Funktionalität des Programms.

## Refactoring Schritte
1. Definition eines Test-Cases
2. Nachschauen ob der aktuelle Code funktioniert. Man sollte ein Backup machen (commiten)
3. Den gewünschten Abschnitt in ein ordentliches Format bringen
4. Nachschaen ob der veränderte Code funktioniert
5. Wenn der Code funktioniert: Den neuen Code commmiten und eine Commit-Message hinzufügen
6. Mit dem refactoring im Code fortfahren

## Prinzipien von guten Code

### Principle of least Astonishment
keine sprechende Klassennamen, usw. verwenden.

### Single Responsibility Principle
Pro Klasse auch nur eine Funktion

## Code Smell
Code Smell heißt schwer verständlicher und schlecht strukturierter Code.

### DRY 
Der Code soll sich nicht wiederholen.

### KISS 
Bei mehreren Möglichkeiten der Problemlösung immer den einfachsten Weg nehmen.

### YAGNI 
Wenn der Code nicht wirklich gebraucht wird, sollte man diesen löschen.

### SoC 
mehrere Problemstellungen in kleiner Probleme aufteilen.

## 10 Code-Smell-Typen

### Zu kurze Bezeichnungen
- ausreichend benennen 

### Zu lange Bezeichnungen
- Man sollte nicht zu lange Bezeichnungen verwenden.

### Tiefe Verschaftelungen
- Verschachtelungen erschweren die Lesbarkeit und Verständlichkeit. 

### Leerzeilen
- Unnötige Zeilen löschen. Zb zu viele Leerzeichen oder Absaetze. 

### Unbenutzter Code
- Unnötiger Code erschwert nur die Verständlichkeit. Löschen!

### Falsche Klammern
- Falsche Klammern können für Errors sorgen.

### Kommentare
- Genügend Kommentare, um den Code zu erklaeren. Man soll aber nicht zu viele verwenden.

### Undurchsichte Bezeichnungen
- Überlegen welche Namen ich verwende. 

### Renundanter Code
- Sich selbst nicht wiederholen

### Zu lange Methoden
- Eine Methode soll nur eine Funktion erfüllen und nicht zuviele Zeilen Code beinhalten.

## Development Platform
- Unity 2019.1.14f1 on macOS High Sierra
- Visual Studio fuer Mac v8.3.11
