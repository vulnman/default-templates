A reflected cross-site scripting (XSS) vulnerability allows the attacker to temporarily inject malicious scripts in the application page.
The typical attack is to send a link to the victim with some JavaScript in it, which will be executed in the victim's browser, inside the vulnerable page.
This malicious JavaScript can, for instance, read the session cookie and send it to the attacker, change the login form and point it to a page controlled by the attacker (and thus stealing the credentials) or even add a non-existent form asking for sensitive data.

Depending on the type of XSS and the nature of the vulnerable application, the impact of this vulnerability can range from temporarily modifying the contents of the website (during the victim's visit) to total control of the victim's session or even of the browser. Given its prevalence and ease of exploitation, it's often considered a serious risk for any application that contains an area that requires authentication.

This type of vulnerability is quite widespread on the Internet and happens when the application takes user input and prints (outputs) it without properly encode or validate that input.