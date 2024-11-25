# Theoretische Fragen 1:

**Was ist Arbeitsspeicher?**

RAM (Random Access Memory), den temporären Speicher in Ihrem Computer, der Anwendungen die Möglichkeit bietet, Daten kurzfristig zu speichern und abzurufen. Ein größerer Arbeitsspeicher bedeutet, dass mehr Daten fast sofort abgerufen und gelesen werden können, anstatt auf die Festplatte geschrieben zu werden.

**Was ist die Speicherhierarchie eines Computers? (mit Diagramm!)**

Die Speicherhierarchie eines Computers sorgt dafür, dass der Computer schnell arbeitet, indem er Daten in verschiedenen Speichern ablegt:

*Register*: Super schnell, sehr klein, direkt in der CPU.

*L1-Cache*: Schnell, speichert oft genutzte Daten, klein.

*L2-Cache*: Etwas größer und langsamer als L1, aber immer noch schnell.

*L3-Cache*: Noch größer und langsamer, geteilt von mehreren Kernen.

*RAM*: Größer, speichert laufende Programme, aber langsamer als Cache.

*Festplatte/SSD*: Sehr groß, aber am langsamsten.

Wichtige Daten sind in den schnellen Speichern, weniger genutzte in den größeren, langsameren.
![Diagramm](Bilder_Infobase/Speicherhierarchie_diagramm.png)

**Wie unterscheidet sich RAM von anderen Speichergeräten wie z.B. der Festplatte?**

RAM und Festplatten sind zwei verschiedene Arten von Speicher in einem Computer:
RAM ist wie ein schneller Notizzettel. Es speichert nur die Dinge, mit denen der Computer gerade arbeitet. Wenn der Computer ausgeschaltet wird, ist alles im RAM weg.
Festplatten sind wie große, langsame Schränke. Sie speichern alle Dateien und Programme für immer, auch wenn der Computer ausgeschaltet ist.

**Welche Arten von RAM gibt es?**

*DRAM*: Der häufigste RAM, er muss immer wieder „aufgefrischt“ werden, um die Daten zu behalten.
*SRAM*: Schneller und stabiler als DRAM, braucht keine Auffrischung, wird in schnellen Speicherbereichen wie dem Cache verwendet.
*DDR RAM*: Eine schnellere Version von DRAM, die in Computern genutzt wird.
*LPDDR RAM*: Eine energiesparende Version von DDR, die vor allem in Handys und Tablets steckt.


# Theoretische Fragen 2:

**1. Was ist SRAM und wie ist SRAM aufgebaut? Nenne Vor- und Nachteile sowie Einsatzgebiete!**

SRAM steht für Static RAM. Es speichert Daten, indem es Transistoren nutzt, die die Daten ohne ständiges Auffrischen behalten.
Aufbau: Es verwendet Schaltungen aus Transistoren, die stabil bleiben und keine Auffrischung brauchen.

Vorteile:
Sehr schnell.
Verbraucht wenig Strom im Vergleich zu DRAM.

Nachteile:
Teurer.
Kann weniger Daten speichern als DRAM.
Einsatzgebiete:

Wird häufig in Cache-Speichern (z.B. in CPUs) verwendet, um Daten schnell zu speichern.

**2. Was ist DRAM und wie ist DRAM aufgebaut? Nenne Vor- und Nachteile sowie Einsatzgebiete!**

DRAM steht für Dynamic RAM. Es speichert Daten in kleinen Kondensatoren, die ständig aufgefrischt werden müssen, damit die Daten erhalten bleiben.
Aufbau: Einfache Transistoren und Kondensatoren, die regelmäßig aufgefrischt werden müssen.

Vorteile:
Billiger und kann mehr Daten speichern als SRAM.

Nachteile:
Langsam im Vergleich zu SRAM.
Muss regelmäßig aufgefrischt werden.
Einsatzgebiete:

Wird als Hauptspeicher (RAM) in Computern, Laptops und Smartphones verwendet.

**3. Was bedeutet “synchroner” RAM?**

Synchroner RAM bedeutet, dass der Speicher mit der Taktfrequenz des Prozessors synchron arbeitet, also immer zur gleichen Zeit wie der Prozessor Daten liest und schreibt.

**4. Nenne Einsatzgebiete von synchronem SRAM bzw. DRAM!**

Synchrones SRAM: Wird in schnellen Cache-Speichern verwendet, die eng mit dem Prozessor zusammenarbeiten.
Synchrones DRAM: Wird in Computern und Laptops als Arbeitsspeicher (RAM) eingesetzt, um schnell Daten zu speichern und abzurufen.