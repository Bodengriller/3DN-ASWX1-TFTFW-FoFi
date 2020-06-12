# 3DN-ASWX1-TFTFW-FoFi
MEINE Änderungen an der 3D-Nexus-TFT-Firmware für den Artillery Sidewinder X1


## Zu diesem Repo
Earl Miller von 3D Nexus bietet auf
https://3d-nexus.com/resources/file-archives/download/5-printer-firmware/11-artillery-swx1-marlin-1-1-9-advanced-firmware-and-gui
seine TFT-Firmware-Modifikation an.

Er hat sich mit seiner Arbeit sehr viel Mühe gegeben.
Seine Firmware wird von vielen Leuten genutzt und ist daher als "erprobt und für gut befunden" anzuerkennen.

Es gab ein paar Kleinigkeiten, die **mir persönlich** nicht 100%ig passten, darum habe ich diese angepasst.

Ich nutze dieses Repo ausdrücklich nur als Speicher-, Ablage- und Dokumentations-Ort für meine eigenen Änderungen.
Dies ist auch der Grund, wieso ich dies hier nur sporadisch und auf Deutsch dokumentiere.  
Diese Änderungen dürfen natürlich von jedermann mit-benutzt werden, allerdings **wird es hier keinen Support geben!**

Bei Fragen zur Firmware wendet euch bitte an Earl Miller von 3D Nexus auf seiner Seite.


## Änderungen
Im Wesentlichen wurden nur Kleinigkeiten geändert:

1. Die Homing-Reihenfolge inkl. Icons

2. Die Anordnung der Buttons im More-Menü

3. Kommentierung der Config

4. Beim Auto-PID-tuning wurden kleine Pausen eingebaut (gab gelegentlich Probleme beim Speichern)

5. Save to Eeprom hat einen Farbumschlag bekommen: Rot -> Speichern -> Grün

6. Name wurde im Bootscreen hinzugefügt (um Verwechslungen zu vermeiden)

![Leveling-Vergleich](https://raw.githubusercontent.com/Bodengriller/3DN-ASWX1-TFTFW-FoFi/master/compare_Tools-Leveling.png)
![More-Vergleich](https://raw.githubusercontent.com/Bodengriller/3DN-ASWX1-TFTFW-FoFi/master/compare_More.png)
  
## Sonstiges  
Test & Forschung ergab;
Babystepping während des Drucks funktioniert, kann allerdings nicht im EEPROM gespeichert werden!  
(M851 ist nicht möglich, wenn MBL aktiviert ist!)  
Näheres dazu: https://github.com/MarlinFirmware/Marlin/issues/3394  
Der "Save to EEPROM" Button im Druckmenü ist also streng genommen überflüssig.
    
## Verlauf  
**12.06.2020** - Erste Überarbeitung/Anpassung der 3D-Nexus-TFT-Firmware
