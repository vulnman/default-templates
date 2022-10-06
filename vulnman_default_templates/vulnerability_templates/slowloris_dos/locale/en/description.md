Slowloris tries to keep many connections to the target web server open and hold them open as long as possible.
It accomplishes this by opening connections to the target web server and sending a partial request.
By doing so, it starves the http server's resources causing Denial Of Service.