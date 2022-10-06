Um eine SQL Injection zu beheben, sollten Sie Prepared Statements verwenden.
Wenn eine Anwendung ausschließlich Prepared Statements verwendet, kann der Entwickler sicher sein, dass keine SQL Injection auftritt.
Prepared Statements kann man sich als eine Art kompilierte Vorlage für die SQL-Abfrage vorstellen, die eine Anwendung ausführen möchte und die mit variablen Parametern angepasst werden kann.

Ein zusätzlicher Bonus ist, dass die Ausführung derselben Abfrage bei mehrmaliger Ausführung sogar schneller ist als ohne Prepared Statements.
Das liegt daran, dass bei der Verwendung von Prepared Statements die Abfrage nur einmal geparst (vorbereitet) werden muss, aber mehrfach mit denselben oder anderen Parametern ausgeführt werden kann.