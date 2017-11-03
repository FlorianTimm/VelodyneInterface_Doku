VelodyneInterface
Bachelorthesis

Kurzzusammenfassung
Die vorliegende Arbeit ist Teil eines Projektes, dass die Entwicklung eines Systems zum
Ziel hat, welches den modular austauschbaren Betrieb verschiedenster Sensorsysteme
an einem Multikopter erlauben soll. Im Speziellen soll hier die Datenschnittstelle von
einem Kompakt-Laserscanner Velodyne Lidar Puck VLP-16 zu einem Einplatinencom-
puter Raspberry Pi entwickelt und implementiert werden. Der Scanner selbst liefert
hierbei die Daten in einem proprietären, binären Format, welche in ein einfach lesbares
Format, hier eine ASCII-Datei, umgewandelt und gespeichert werden sollen. Außerdem
sollen die Daten mit einem eindeutigen Zeitstempel versehen werden, um diese später
mit anderen Sensorsystemen verknüpfen zu können. Diese Datentransformation sollte
möglichst simultan zur Aufnahme erfolgen.
Auch Teil der Arbeit ist die Schaffung einer Steuerung der Aufnahme des Lasers-
canners. Hierfür wurde ein Bedienmodul entwickelt, welches am Raspberry Pi direkt
angeschlossen werden kann, sowie eine Steuerungsweboberfläche eingebunden, die die
Steuerung während des Fluges ermöglichen soll.

Abstract
The present work is part of a project aimed the development of a system that allows
the modular interchangeable operation of various sensor systems on a multicopter. In
particular, the data interface for compact laser scanner Velodyne Lidar Puck VLP-16 to
a single-board computer Raspberry Pi will be developed and implemented. The scan-
ner itself provides the data in a proprietary, binary format, which should be converted
and stored into an easy-to-read ASCII file. In addition, the data should be provided
with a unique timestamp in order to be able to link it later with other sensor systems.
This data transformation should be carried out as simultaneously as possible while
recording.
Also part of the work is the creation of a control of the recording of the laser scanner.
For this purpose, an operating module was developed, which can be connected directly
to the Raspberry Pi, as well as a web control surface integrated in the software, which
should enable the control during the flight.
