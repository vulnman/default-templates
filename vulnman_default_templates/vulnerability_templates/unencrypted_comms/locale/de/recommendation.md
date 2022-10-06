Die Anwendung sollte so konfiguriert werden, dass sie bei der gesamten Kommunikation Verschlüsselung verwendet.
Dies bedeutet normalerweise, dass der Dienst so konfiguriert wird, dass TLS mit einer geeigneten Auswahl an Chiffren verwendet wird, so dass alle eingehenden Anfragen im Klartext (ohne Verschlüsselung) an den TLS-Endpunkt der Anwendung umgeleitet werden müssen.

Bei HTTP wird dies mit einer 301 Moved Permanently-Anweisung erreicht.
Sie kann durch einen HTTP Strict Transport Security Header (HSTS) ergänzt werden, um die Browser zu zwingen, alle Anfragen in HTTPS zu stellen, auch wenn der Endnutzer vergisst, HTTPS in die Anfrage zu schreiben.