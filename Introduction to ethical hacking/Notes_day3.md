### Notes:

---

#### Day3

* Ethical hacking across Domains:
  * Web application environment.
  * Network architecture.
  * Mobile Applications.
  * IOT - Internet of things.
  * and many more...

---

### Web application domain : 


* Two major categories -
  * `Client side vulnerabilities`
  * `Server side vulnerabilities`

* All the attacks can be categorised into 3 major attacks:-
  * Parameter tampering
  * Unvalidated inputs
  * Directory tranversal attacks  



Eg of Client side vuln - CSS, XSS.  (Cross site scripting)
` A CSS Injection vulnerability involves the ability to inject arbitrary CSS code in the context of a trusted web site which is rendered inside a victim's browser.`  
Server side vuln - SQL injection, PHP injection.

### Parameter tampering - 
The attacker is sitting in the middle.    
You send a request from client and get a response from the server. The hacker will try to sniff or read your data being in the middle.  

### Unvalidated input -
The attack where hackers try to provide some inputs that are not validated or authenticated.  
Let's suppose we have a login box in some xyz.com website !!. He can use HTML or a JS injection.   
`<script>"You are hacked"</script>` or  
`<iframe src="some website"></iframe>`

### Directory Transversal attack -
This is related to operating system and is more complex. It is very common attack.   
Example- a site exposed to operations or related to DNS system.   

---

Thank you
