The correct prevention method is to escape the user input data before including it in the response, however there are some rules you must follow to ensure proper escaping is applied.

If you are using a template system to define the look and layout of your application, it is likely that it has support for auto-escaping data, without much hassle.
Depending on the system, you either enable it globally when loading the template system or you have to enable it everything time you echo some code or variable in the page.

Using a template system to generate your pages will probably save you some time and it easier to ensure that is XSS-free, since most of them auto-escape by design, such as the template system used in the Python framework Django.

If you have to do it by hand you must be aware that there isn't one-size-fits-all solution: the way you escape the input depends on the context of the page where it is being placed.

It is recommended to have a look at the [OWASP Guide](https://cheatsheetseries.owasp.org/cheatsheets/Cross_Site_Scripting_Prevention_Cheat_Sheet.html), which gives good tips on how to prevent XSS vulnerabilities.
