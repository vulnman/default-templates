Die Software verwendet externe Eingaben, um einen Pfadnamen zu konstruieren, der eine Datei oder ein Verzeichnis identifizieren soll, das sich unterhalb eines beschränkten übergeordneten Verzeichnisses befindet, aber die Software neutralisiert spezielle Elemente innerhalb des Pfadnamens nicht ordnungsgemäß, die dazu führen können, dass der Pfadname zu einem Ort außerhalb des beschränkten Verzeichnisses aufgelöst wird. 

Viele Dateioperationen sollen innerhalb eines beschränkten Verzeichnisses stattfinden.
Durch die Verwendung spezieller Elemente wie ".." und "/"-Trennzeichen können Angreifer aus dem eingeschränkten Verzeichnis ausbrechen, um auf Dateien oder Verzeichnisse zuzugreifen, die sich an anderen Stellen des Systems befinden.

Eines der gebräuchlichsten speziellen Elemente ist die "../"-Sequenz, die in den meisten modernen Betriebssystemen als das übergeordnete Verzeichnis des aktuellen Speicherorts interpretiert wird.
Dies wird als relatives Pfad-Traversal bezeichnet.

Die Pfadüberquerung umfasst auch die Verwendung von absoluten Pfadnamen wie "/usr/local/bin", die beim Zugriff auf unerwartete Dateien nützlich sein können.
Dies wird als absolute Pfadüberquerung bezeichnet. 
