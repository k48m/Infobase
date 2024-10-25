# Praktisch Aufgabe 1:

Nimm dir einen beliebigen Tower-PC aus dem Lager und öffne die BIOS/UEFI-Einstellungen.
Mach von jeder Seite der Einstellungen Photos und erkläre, was sich auf dieser an Einstellungen festlegen lässt.
Erkläre - insofern möglich - jede Einstellungsmöglichkeit in deinem BIOS!

[BIOS/UEFI](Bilder_Infobase/BIOS_UEFI.png)

[BIOS/UEFI](Bilder_Infobase/BiosTool.png)

[BIOS/UEFI Boot](Bilder_Infobase/BiosBoot.png)

[BIOS/UEFI Monitor](Bilder_Infobase/BiosMonitor.png)

[BIOS/UEFI Advanced](Bilder_Infobase/BiosAdvanced.png)

[BIOS/UEFI AiTweaker](Bilder_Infobase/AiTweaker.png)

[BIOS/UEFI Main](Bilder_Infobase/BiosMain.png)

## Beantworte danach folgende Fragen und dokumentiere evtl. geforderte Prozesse!

**1.	Wo ändert man die Uhrzeit im BIOS/UEFI?**

    •	BIOS-Öffnen

    •	Erweitert Einstellungen 

    •	Main

    •	System Date und System time 

**2.	Welche Spannungen sind für den Computer wichtig und wo sieht man diese?**

    •	Erweiterte Einstellungen

    •	Monitor 

    •	Da stehen die einzahlen Spannungen am Main

**3.	Wo kann man einstellen, dass das System nach einem Stromausfall automatisch wieder hochfährt und wieso sollte man das wollen?**

    •	Erweiterte Einstellungen 

    •	Boot 

    •	Bei Boot Configration auf next Boot after AC Power loss

    •	Entweder normal Boot oder Fast Boot

    •	Normalboot: Bootet normal nach einen Strom Unfall

    •	Fast Boot: startet von alleine nach einem Strom Ausfall 

**4.	Was ist die Bootreihenfolge und wo ändert man diese?**

    •	Erweiterte Einstellungen

    •	Boot 

    •	Boot Option Priorties

    •	Dort kann man die Boot Reihenfolge Ändern 

**5.	Wo kann man die grundlegenden Informationen über verbaute Hardware im BIOS/UEFI finden?**

    •	Erweiterte Einstellungen 

    •	Main

    •	Dort wird die grundlegenden Hardware Informationen angezeigt 

**6.	Wo kann man die Frontpanel-USB-Anschlüsse deaktivieren?**

    •  	Erweiterte Einstellungen 

    •	Advanced 

    •	USB Configuration 

    •	Ganz unten in USB Single Port control rein gehen.

    •	Beliebige USBs ein/ausschalten 

**7.	Wo kann man den Num-Lock standardmäßig anschalten?**

    •	Advanced settings

    •	Boot

    •	Bootup num-lock state 

    •	On/off

**8.	Wo kann man die Onboard-Netzwerkkarte deaktivieren?**

    •	Erweiterte Einstellungen 

    •	Advanced 

    •	Onboard Deviices Configuration 

    •	Realtek LAN Controller ein/ausschalten 

**9.	Wo kann man die Lüfter des Systems regeln und welche Vorteile bringt das?**

    •	Erweiterte Einstellungen 

    •	Monitor 

    •	Bisschen runter scrollen 

    •	CPU fan speed low limit 

**10.	Wo kann man ein BIOS-Passwort setzen? Welche Vorteile bringt das setzen eines BIOS-Passworts?**

    •	Erweiterte Einstellungen

    •	Main 

    •	Security

    •	Administrator Password für BIOS/UEFI Setup

    •	User Password für einschalten, er fragt bevor er bootet für ein Passwort

**11.	Was ist Wake-on-LAN und wo schaltet man dieses ein oder aus?**

Wake on LAN (WoL) ist ein Netzwerkstandard, mit dem ein Computer aus der Ferne eingeschaltet werden kann - unabhängig davon, ob er sich im Ruhezustand befindet oder sogar vollständig ausgeschaltet ist. Das funktioniert über den Empfang eines sogenannten "Magic Packets", das von einem WoL-Client gesendet wird.

**12.	Was ist SecureBoot und wofür sollte man dies aktivieren bzw. deaktivieren?**

Aktivieren Sie Secure Boot (Sicherer Start), um Malware-Angriffe, Virusinfektionen oder die Verwendung nicht vertrauenswürdiger Hardware oder bootfähiger USBs zu blockieren, die dem Computer Schaden zufügen können.

**13.	Was ist CSM Support und wofür sollte man dies aktivieren bzw. deaktivieren?**

CSM existiert (Compatibility Support Module), um die Kompatibilität mit Systemen zu gewährleisten, die UEFI vollständig unterstützen oder nicht unterstützen, sowie mit Systemen, die in Legacy installiert werden müssen. Wenn Sie also ein herkömmliches MBR-Gerät booten müssen, müssen Sie CSM aktivieren.

**14.	Was ist Fast Boot und wofür sollte man dies aktivieren bzw. deaktivieren?**

Wenn Sie diese Funktion aktivieren, werden alle Dateien Ihres Computers in den Ruhezustand versetzt und beim nächsten Start dort fortgesetzt, wo er aufgehört hat. Wenn der Schnellstart aktiviert ist, wird der Computer jedoch nicht vollständig heruntergefahren.

**15.	Was ist SMT bzw. Hyperthreading und wieso sollte man es aktivieren bzw. deaktivieren?**

SMT (Simultaneous Multithreading) und Hyper-Threading sind Technologien, die es einem Prozessor ermöglichen, mehrere Aufgaben gleichzeitig zu bearbeiten. 

**Wie es funktioniert:**

*   Ein physischer Prozessor-Kern kann zwei "virtuelle" Kerne (Threads) simulieren.
*   Dadurch können mehr Aufgaben gleichzeitig erledigt werden.

**Vorteile:**

*   **Schneller**: Programme, die mehrere Threads nutzen, laufen oft schneller.

*   **Bessere Nutzung**: Die CPU wird effizienter eingesetzt, da weniger Leerlauf entsteht.

**Nachteile:**

*   **Wettbewerb um Ressourcen**: In manchen sehr rechenintensiven Anwendungen kann es zu Leistungseinbußen kommen.

*   **Komplexität**: Es kann schwieriger sein, Fehler zu finden.

**Aktivieren oder Deaktivieren?**

*   **Aktivieren**: Wenn du viele Programme nutzt, die Multithreading unterstützen (z.B. Spiele, Videoschnitt).

*   **Deaktivieren**: Wenn du meist einfache Programme nutzt oder Probleme feststellst.

**16.	Was bringt ein BIOS/UEFI-Update und was ist dabei zu beachten?**

UEFI steht für Unified Extensible Firmware Interface. Es sieht ähnlich aus wie alte BIOS-Menüs, ermöglicht es Ihnen jedoch, die Maus zu verwenden und einfacher zwischen den Untermenüs zu navigieren. Hinter den Kulissen ermöglicht es schnellere Startzeiten, einfachere Updates und bessere Sicherheit.

**17.	Wie führt man ein BIOS-Update durch?**

**Vorbereitungen**

*   **Überprüfe die BIOS-Version**: Starte deinen Computer und gehe ins BIOS (meist durch Drücken von F2, DEL oder ESC beim Hochfahren). Notiere die aktuelle Version.

*   **Modell und Hersteller**: Finde das genaue Modell deines Motherboards heraus. Diese Infos findest du meist im Handbuch oder auf der Website des Herstellers.

**Treiber und Updates suchen**

*   **Herstellerseite besuchen**: Gehe auf die Website des Motherboard-Herstellers und suche nach deinem Modell.
*   **BIOS-Updates**: Lade die neueste BIOS-Version herunter, wenn es eine aktuellere gibt.

**Backup erstellen**

*   **Wichtige Daten sichern**: Erstelle ein Backup deiner wichtigen Dateien, falls während des Updates etwas schiefgeht.

*   **Update-Medium vorbereiten**

*   **USB-Stick**: Formatiere einen USB-Stick im FAT32-Format und kopiere die BIOS-Datei darauf.

**BIOS-Update durchführen**

*   **Starte den Computer neu** und gehe wieder ins BIOS.
*    **Finde die Option für BIOS-Updates**: Das kann „EZ Flash“, „M-Flash“ oder ähnlich heißen.
*   **Wähle die BIOS-Datei** auf dem USB-Stick aus.
*   **Beginne das Update**: Folge den Anweisungen auf dem Bildschirm. Unterbreche den Vorgang nicht!

**Nach dem Update**

*   **Neustart**: Der Computer startet möglicherweise automatisch neu.

*   **BIOS-Einstellungen überprüfen**: Gehe erneut ins BIOS und überprüfe die Einstellungen. Setze sie bei Bedarf zurück oder ändere sie nach deinen Wünschen.