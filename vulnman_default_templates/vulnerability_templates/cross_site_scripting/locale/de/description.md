Eine reflektierte Cross-Site-Scripting-Schwachstelle (XSS) ermöglicht es dem Angreifer, vorübergehend bösartige Skripte in die Anwendungsseite einzuschleusen.
Der typische Angriff besteht darin, dem Opfer einen Link mit einem JavaScript zu schicken, das im Browser des Opfers innerhalb der anfälligen Seite ausgeführt wird.
Dieses bösartige JavaScript kann beispielsweise den Sitzungs-Cookie auslesen und an den Angreifer senden, das Anmeldeformular ändern und auf eine vom Angreifer kontrollierte Seite verweisen (und so die Anmeldedaten stehlen) oder sogar ein nicht vorhandenes Formular hinzufügen, in dem sensible Daten abgefragt werden.

Je nach Art des XSS und der anfälligen Anwendung können die Auswirkungen dieser Schwachstelle von einer vorübergehenden Änderung des Inhalts der Website (während des Besuchs des Opfers) bis hin zur vollständigen Kontrolle über die Sitzung des Opfers oder sogar über den Browser reichen. Aufgrund ihrer Verbreitung und leichten Ausnutzung wird sie oft als ernstes Risiko für jede Anwendung betrachtet, die einen Bereich enthält, der eine Authentifizierung erfordert.

Diese Art von Sicherheitslücke ist im Internet recht weit verbreitet und tritt auf, wenn die Anwendung Benutzereingaben entgegennimmt und ausgibt, ohne diese Eingaben ordnungsgemäß zu verschlüsseln oder zu überprüfen.
