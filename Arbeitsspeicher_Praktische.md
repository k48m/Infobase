# Praktische Fragen 2:

**1.Wie viel Arbeitsspeicher ist verbaut?**

BIOS/UEFI unter "Memory" nachsehen.
12 GB (12.288 MB)

**2. Welchen Typ hat der Arbeitsspeicher?**

Unter Main finden wir die Informationen von RAM!
DDR3

**3. Mit wie vielen MT/s taktet der Arbeitsspeicher derzeit?**

1372 MHz (Effektiv: 1372 MT/s)
(1372 * 2= 2744 MT/s)

**4. Was ist die Höchste vom Arbeitsspeicher unterstützte Taktrate in der derzeitigen Kombination aus Mainboard/CPU/RAM?**

Unter AI Tweaker finden wir die Höchste Taktrat.
Synchronizing Target CPU Turbo-Mode Speed: 4100 MHz
Taget DRAM-Speed: 1372 MHz 

**5. Unterstützt der RAM profilbasiertes Übertakten (XMP)?**

Nicht ersichtlich (im BIOS Ai Tweaker prüfen).

**6. Unterstützt das Mainboard das freie Übertakten des Arbeitsspeichers?**

Ja, freies Übertakten möglich (im BIOS Ai Tweaker prüfen).

**7. Welche anderen Einstellungen können, vorgenommen werden?**

CAS Latency (CL)
RAS to CAS Delay (tRCD)
RAS Precharge (tRP)
RAS Active Time (tRAS)
Command Rate (CR)
 
DRAM CAS# Latency (CL): Anzahl der Taktzyklen, die benötigt wird, um auf einen Datensatz im DRAM zuzugreifen und ihn verfügbar zu machen.


Niedrigere CAS-Latenz = schnellere Datenzugriffe.

CAS-Latenz immer in Kombination mit Speicherfrequenz betrachten.

DRAM RAS# zu CAS# Delay (tRCD): Zeitverzögerung zwischen dem Aktivieren einer Zeile (RAS) und dem Zugreifen auf die Spalte (CAS).

Niedriger tRCD-Wert = schnellere Leistung.

DRAM CLK Period: Zeitintervall für einen vollständigen DRAM-Taktzyklus.

Inverse der Taktfrequenz (z. B. 1600 MHz = 0,625 Nanosekunden pro Zyklus).

tRRSR (Turnaround Delay from Read to Read): Verzögerung zwischen zwei aufeinanderfolgenden Lesevorgängen im RAM.

Wichtig für reibungslose Datenabfragen und optimale Leistung.

DRAM Write Recovery Time (tWR): Zeitintervall zwischen dem Abschluss eines Schreibvorgangs und der erneuten Verfügbarkeit des Speicherblocks.

Stellt sicher, dass die Daten korrekt geschrieben und stabil sind.


# Praktische Aufgabe 4:

In dieser Aufgabe haben wir getestet, wie sich ein Computer mit defektem Arbeitsspeicher verhält.
Zuerst wurde ein Testaufbau mit folgender Hardware realisiert:

•	Mainboard (P8Z77-V PRO | Motherboards | ASUS USA)

•	Prozessor (Intel „R“ Core „TM“ i7-3770 CPU 3.40GHz)

•	Netzteil (300W)

•	TL460s Plus

Es wurde keine Festplatte verwendet, das Betriebssystem wurde von USB geladen.
•	USB (Memtest 86 +)

Vor Beginn des Tests wurden alle Komponenten auf ihre Funktion getestet. Folgendes Verhalten wurde festgestellt:

Hier einfügen: Funktionsbeschreibung, wie verhält sich der Computer, wenn der Arbeitsspeicher korrekt funktioniert?

BIOS erkennt die RAM-Kapazität.

Keine Fehlermeldung im POST.

Der Computer läuft stabil ohne Fehler.

•	Gibt es irgendwelche Signale, welche sich bemerkbar machen?

Akustische BIOS-Signale.

Fehlermeldungen beim Booten

•	Welchen POST-Code sehen wir?

5.5 wen etwas im RAM nicht funktioniert 

A.0 funktioniert (RAM)

•	Wie verhalten sich etwaige OnBoard-Geräte wie Lüfter, LEDs, etc?

Lüfter werden ein-ausgeschaltet.

LEDs werden ROT leichten.
 

Test 1: Defekter RAM 1
Der erste defekte Arbeitsspeicher, der getestet wurde, war mechanisch beschädigt.
Hier Bild vom RAM einfügen und Fehler beschreiben!
 
Welche Pins sind defekt und welche Funktion haben diese?

Von 111 bis 117 defekt sind.

|PINS|FRONT|
-----|-----|
|111 |VDD  |
|112 |VDD  |
|113 |WE   |
|114 |S0   |
|115 |CAS  |
|116 |ODT0 |
|117 |VDD  |

Wie hat sich der Computer mit diesem Arbeitsspeicher verhalten?

Startproblemen

Fehler bei RAM-Tests

Welche Fehlertöne, POST-Codes und anderes Verhalten haben das System gezeigt?

Memory error (Keine Anzeige auf dem Monitor).

System bleibt beim Booten hängen.

Wiederholte Neustarts oder Hängenbleiben.

War es egal in welchem Slot der RAM gesteckt wurde?

Nein

Man muss alle Slots testen!


Test 2: Defekter RAM 2

RAM-Slot 1 funktioniert nicht

Hat bei (TL460s Plus) 5.5 gezeigt.

RAM-Slot 1 funktioniert nicht

Hat bei (TL460s Plus) 5.5 gezeigt.

LEDs werden ROT leichten.

Test 3: Defekter RAM 3

RAM-Slot 1 funktioniert nicht

Hat bei (TL460s Plus) 5.5 gezeigt.

LEDs werden ROT leichten.

Lüfter werden ein-ausgeschaltet und schneller.

Abschließende Notizen

Wie hat sich der Computer bei defektem Arbeitsspeicher verhalten?

Keine Screens und ist Abstürze.

Startprobleme, der Computer blieb häufig hängen oder konnte nicht booten.


Welche Tools zur Diagnose haben wir eingesetzt? Soft- & Hardware?

MemTest86+ Überprüfung auf fehlerhafte Speicherzellen.

POST-Codes: Durch den PC-Lautsprecher (BEEP-Codes) oder Diagnose-LEDs auf dem Mainboard.

Testen mit funktionierendem RAM, um den Fehler zu isolieren.

Fehlerdiagnose

Zum Feststellen von Fehlern beim Arbeitsspeicher geht man wie folgt vor:

•	Zuerst auf eine minimale Bestückung reduzieren (nur einen RAM testen!)

•	Verschiedene Slots durchprobieren

•	Slots reinigen (Blasebalg oder vorsichtig mit Druckluft)

•	Getestete, funktionierende Hardware Einbauen und das Verhalten überprüfen

•	RAM in anderem System testen.

•	BIOS zurücksetzen.

•	MemTest86+ ausführen.

•	Spannung und Kompatibilität prüfen.

•	RAM-Module und Slots wechseln.

•	Systemkomponenten prüfen.

•	Speichermodul auf sichtbare Schäden überprüfen.

•	Motherboard auf Kurzschlüsse prüfen.
