# WebserviceChecklist
things your app should have before shipping

* Configure Content Security Policy - Content Security Policy (CSP) is a great new HTTP header that controls where a web browser is allowed to load content from and the type of content it is allowed to load. It uses a white-list of allowed content and blocks anything not in the allowed list. It gives us very fine grained control and allows us to run our site in a sandbox in the users browser.
* Configure Site-wide HTTPS - Please note that SSL has been superseded by TLS. SSL is vulnerable to the POODLE security vulnerability and should not be used. These steps outline how to secure your site so that all requests and responses are made over HTTPS using TLS, you should consider using it across your whole site for best security, rather than having a mix of HTTP and HTTPS pages. 
* Understand OWASP Top 10 - Understand the top ten security vulnerabilities and how you can protect yourself from them at OWASP Top 10. Also take a look at the OWASP [Top Ten Cheat Sheet](Understand OWASP Top 10 - Understand the top ten security vulnerabilities and how you can protect yourself from them at OWASP Top 10. Also take a look at the OWASP Top Ten Cheat Sheet. ). 
* Understand Cross Site Scripting (XSS) - Understand Cross Site Scripting (XSS) security vulnerabilities and how you can protect yourself. 
* Understand Cross Site Request Forgery (CSRF) - Understand Cross Site Request Forgery security vulnerabilities and how you can protect yourself.
* Upload static files to CDN
* Configure Caching
* Robots.txt?
* Sitemap.xml?
* API's have swagger specs
* ETags are understood, and are enabled if needed 
