### Notes:

---

Day 5

### Demonstration - SQL Injection

1. Run the happy cycle. (`In our case, we tried logging in using admin admin which showed invalid credentials`).
2. Try to see URL, Errors, Console and Cookies. (`Nothing feasible in this too`).
3. View the page source. (`Different files, js, css, input tags`).
4. Try characters like ' " ) } -- ## (`We are given a SQL syntax error`) ( In our case, we used - ' OR '1' = '1)


* Why are web app a target ??
  * Very easily available via the internet.
  * Mission-critical bussiness sensitive data (Eg-banks).
  * Always running.
  * Often direct access to backend data.
  * Traditional firewalls and SSL provide no protection.
  * Many applications are custom-made --> vulnerabilities.

---

### What is bWAPP ?

* bWAPP stands for buggy wep application !!
* Deliberately insecure web app containing all kinds of vulnerabilities.
* It is for practise to help enthusiasts, developers and students discover and prevent issues.
* For penetration testing, and ethical hacking projects.

* bWAPP architecture : 
  * Open source PHP application.
  * Backend MySQL database.
  * Hosted on Linux/Windows with Apache/IIS.
  * Supported on WAMP or XAMPP.

* Features:
  * Easy to use.
  * Easy to understand.
  * Well structured and documented PHP code.
  * Different security levels. (low/medium/high)
  * New user creation.
  * Reset app or database feature.
  * Manual intervention page.
  * Email functionalities.
  * Local PHP setting files.
  * No - authentication mode (A.I.M)
  * 'Evil bee' mode, bypassing security.
  * 'Evil' directory, including attack scripts.
  * WSDL file.
  * Fuzzing possibilities.

bWAPP has more than 70 bugs !
Covering all major known web vuln.

OWASP - Open Web Application Security Project.
Worldwide ngo focused on improving the security of software.
freely available articles, methodologies, documentations, tools and technologies.

---

Thank you


