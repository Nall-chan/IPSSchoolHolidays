# Schulferien

Dieses Modul zeigt an, ob es sich heute um einen Feiertag handelt.
Im Konfigurationsformular muss das Bundesland ausgew�hlt werden.

## Dokumentation

**Inhaltsverzeichnis**

1. [Funktionsumfang](#1-funktionsumfang) 
2. [Voraussetzungen](#2-voraussetzungen)
3. [Installation](#3-installation)
4. [Funktionsreferenz](#8-funktionsreferenz) 
5. [Anhang](#5-anhang)

## 1. Funktionsumfang

 �ber die Webseite [http://www.schulferien.org](http://www.schulferien.org) wird ermittelt ob heute Schulferien sind.  
 Entsprechend werden die beiden Statusvariablen mit Werten gef�llt.  

## 2. Voraussetzungen

 - IPS 4.x
 
## 3. Installation

   - IPS 3.x  
        Kein Modul, aber das Original-Script aus dem Forum kann genutzt werden.
        [IP-Symcon Forum: Schulferien](https://www.symcon.de/forum/threads/20398-Schulferien)

   - IPS 4.x  
        �ber das 'Modul Control' folgende URL hinzuf�gen:  
        `git://github.com/Nall-chan/Schulferien.git`  


## 4. Funktionsreferenz

```php
SCHOOL_Update( interger $InstanceID );
```
 Startet eine neue Pr�fung ob Ferien sind.  

## 5. Anhang

**GUID's:**  
 `{3B2628A3-AA47-431F-BF65-074C7002174B}`

**Changelog:**  
 Version 1.0:
  - Erstes Release

**Danksagung:**  
 An Kronos aus dem IPS-Forum f�r das Original-Script.
