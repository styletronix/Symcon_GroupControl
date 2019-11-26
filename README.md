# SX_SymconExtension

Dies ist ein Modul für IP-Symcon, um dessen funktionalität zu erweitern. 
Mindestvoraussetzung IP-Symcon 5.0

## Gruppensteuerung
Die Gruppensteuerung ermöglicht das gleichzeitige Schalten mehrerer Endgeräte. Der primäre Zweck ist die Steuerung von Beleuchtung oder Rollos. Allerdings kann die Gruppensteuerung auch universell für andere Zwecke eingesetzt werden. z.B. überall dort, wo der Maximalwert mehrerer Geräte benötigt wird.

Die Gruppensteuerung kann für komplexe Aufgaben kaskadiert werden. Das bedeutet dass eine Gruppe aus mehreren Untergruppen bestehen kann.

[Weitere Details zur Gruppensteuerung](/Gruppensteuerung/Readme.md)

## Alarmanlage
Die Alarmanlage wurde einer klassischen Alarmanlage nachempfunden und bietet unter anderem folgende Möglichkeiten.

Alarmzonen unterteilt in 24h-Alarm (Rauchmelder / Technik / Sabotage), Technik-Alarm und Einbruch-Alarm.
Eingangs- und Ausgangsverzögerung je nach ausgelöstem Sensor.
Vorwarnung bei der Eingangs- und Ausgangsverzögerung.
Ansteuerung von Sirenen, Warnlichtern und Alarmbeleuchtung mit unterschiedlicher Dauer bis zur automatischen Deaktivierung. (gesetzlich vorgeschrieben)
Alarm-Sperre bei zu häufiger auslösung bis zum Reset. (gesetzlich vorgeschrieben)
Betriebsmodus: Deaktiviert, Aktiviert, Intern Aktiviert und Wartung.
Statustext zur Nutzung in Text-To-Speech systemen oder Anzeige auf einem Display.


[Weitere Details zur Alarmanlage](/Alarmanlage/readme.md)


## Treppenhauslicht
Die Treppenhauslicht-Steuerung ermöglicht das einschalten eines Lichts per Taster und zeitgesteuerte ausschalten mit Vorwarn-Funktion vor dem ausschalten, welche für Mietshäuser gesetzlich vorgeschrieben ist.

Es können mehrere Geräte als Tasterund Schaltausgang verwendet werden.

[Weitere Details zum Treppenhauslicht](/Treppenhauslicht/readme.md)

## Aufwachlicht
Per Zeitinterval z.b. 7 Uhr morgens, wird ein Licht in einem vordefinierten Zeitraum (z.b. 30 Minuten)  von 0 bis 100% eingeschaltet. Nach einer definierbaren Einschaltdauer wird das Licht wieder ausgeschaltet. Dient zum sanftem aufwecken mit einem dimmbaren Licht.

[Weitere Details zum Aufwachlicht](/Aufwachlicht/readme.md)
