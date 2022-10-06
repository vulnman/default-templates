Die korrekte Verhinderungsmethode besteht darin, die Benutzereingabedaten zu entschlüsseln, bevor sie in die Antwort aufgenommen werden.

Wenn Sie ein Vorlagensystem verwenden, um das Aussehen und das Layout Ihrer Anwendung zu definieren, ist es wahrscheinlich, dass es ohne großen Aufwand Unterstützung für das automatische Escapen von Daten bietet.
Je nach System aktivieren Sie diese Funktion entweder global beim Laden des Vorlagensystems oder Sie müssen sie jedes Mal aktivieren, wenn Sie einen Code oder eine Variable auf der Seite ausgeben.

Die Verwendung eines Vorlagensystems zur Generierung Ihrer Seiten spart Ihnen wahrscheinlich etwas Zeit und es ist einfacher sicherzustellen, dass die Seiten XSS-frei sind, da die meisten von ihnen von vornherein Auto-Escapen, wie z. B. das Vorlagensystem im Python-Framework Django.

Wenn Sie es von Hand machen müssen, müssen Sie sich darüber im Klaren sein, dass es keine Einheitslösung gibt: Die Art und Weise, wie Sie die Eingabe entschlüsseln, hängt vom Kontext der Seite ab, auf der sie platziert wird.

Es wird empfohlen, einen Blick in den [OWASP-Leitfaden](https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html) zu werfen, der gute Tipps zur Vermeidung von XSS-Schwachstellen enthält.
