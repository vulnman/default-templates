To fix an SQL Injection you should use Prepared Statements.
If an application exclusively uses prepared statements, the developer can be sure that no SQL injection will occur.
Prepared Statements can be thought of as a kind of compiled template for the SQL that an application wants to run, that can be customized using variable parameters.

As an added bonus, if you're executing the same query several times, then it'll be even faster than when you're not using prepared statements.
This is because when using prepared statements, the query needs to be parsed (prepared) only once, but can be executed multiple times with the same or different parameters.