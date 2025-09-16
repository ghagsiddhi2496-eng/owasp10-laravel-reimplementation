# owasp10-laravel-reimplementation
MITIGATINGOWASP TOP 10 VULNERABILITIES INCORE PHP APPLICATIONS THROUGH SECURE LARAVEL REIMPLEMENTATION

This study critically examines the security implications of migrating a vulnerable core PHP
web application to the Laravel framework through a controlled comparative case study. The
baseline application, derived from the PentesterLab “Web for Pentester” ISO, was
deliberately insecure and contained common vulnerabilities including SQL Injection, Cross- Site Scripting (XSS), LDAP injection, code and command injection, file inclusion, and unsafe
file upload mechanisms. A functionally equivalent Laravel re-implementation was then
developed, adhering to the framework’s secure defaults such as Eloquent ORM, Blade
template with automatic output escaping, CSRF protection, and validation rules. Both
implementations were subjected to identical testing methodologies using manual
exploitation, with Burp Suite employed for the interception and analysis of HTTP requests
and responses to ensure consistency and internal validity. 

The findings demonstrate that Laravel security features significantly reduce the
exploitability of vulnerabilities prevalent in the core PHP baseline. In particular, injection- based flaws and XSS vectors were effectively mitigated through the framework’s default
mechanisms. However, the research also highlights important limitations: the security
benefits are contingent on correct implementation, and the analysis is restricted to a single
application case study, which limits broader relevance. 

This project contributes empirical evidence to the debate on the role of frameworks in web
application security by moving beyond theoretical claims to experimentally validated
outcomes. It underscores Laravel effectiveness in addressing categories of vulnerabilities
mapped to the OWASP Top 10, while also cautioning that framework adoption alone does
not guarantee security without disciplined development practices. The work provides a
practical foundation for future research to extend the comparative approach to broader
PHP ecosystems and diverse real-world applications. Keywords: Cross-site Scripting (XSS), SQL Injection (SQLi), Lightweight Directory Access
Protocol (LDAP), PentesterLab ISO, Vitual Machine (VM), Model–View–Controller


Laravel code aviable here - https://drive.google.com/file/d/1mmqyVe4_wBMdKC2Awp67dc5g9FGhiptA/view?usp=sharing
Architecture (MVC), Eloquent Object–Relational Mapping (Eloquent ORM), Cross-Site
Request Forgery Protection (CSRF), Open Web Application Security Project (OWASP).
