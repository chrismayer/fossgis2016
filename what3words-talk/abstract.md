# Die Adressierung der Welt

## What3Words und die Integration in Open Source GIS Software

Adressen als Kombination einer Straßen- oder Platzangabe und einer Hausnummer sind in Deutschland flächendeckend verfügbar und werden als selbstverständlich gesehen. Dies gilt jedoch nicht für die gesamte Welt. Beispielsweise gibt es in vielen Entwicklungsländern keinerlei standardisierte Adressen. Vielmehr werden dort auch offizielle Gebäude mit Wegbeschreibungen a la "Hinter dem großen gelben Gebäude rechts und dann nach der dritten Straße links" adressiert. Auch nach katastrophalen Ereignissen, wie Hochwasser oder Erdbeben, welche eine zerstörte Infrastruktur nach sich ziehen, funktioniert das übliche Adressierungssystem meist nicht mehr. Dies stellt gerade für die Koordinierung der Rettungseinsätze ein großes Problem dar.

Hier hilft das neuartige Adressierungssystem "what3words" [1]. what3words (w3w) stellt ein weltweites Netz von 57 Billionen Quadraten mit einer Größe von 3x3 Metern bereit, wobei jedes Quadrat mit einer Kombination aus drei Wörtern addressiert wird. Somit ist what3words eine alternative Georeferenz zu bestehenden Koordinaten oder Adressen. Vorteil dabei ist, dass die what3words Adressen leicht zu merken und somit einfach zu teilen sind. Über einen Algorithmus (implementiert in diversen APIs) kann jede w3w-Adresse wieder in geographsiche Koordinaten überführt werden, was die gemeinsame Nutzung mit "klassischen" Geodaten erlaubt.

Der Vortrag beleuchtet what3words im Detail und präsentiert, ob und wie w3w mit gängiger Open Source GIS Software (QGIS, OpenLayers, etc.) bereits genutzt werden kann.

* [1] https://what3words.com/

