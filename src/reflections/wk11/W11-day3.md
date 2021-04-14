What is SQL injection?
It is a way for malicious individuals to damage, corrupt or otherwise delete an SQL data base. 

What are 3 methods SQL injection can be done by?
All forms if SQL injection involve inserting arbitrary code into a user input field to delete copy or modify the database. THe second form of injection involves Cookies. Cookies are stored on local machines, and hackers can use accepted cookies to insert "msaleware' or sql code into the back end database. HTTP headers can also be used to insert code code into the string if the web application fails to sanitize those inputs as well.


How can we detect and sanitize SQL injection attacks?

One can use a Web Application Firewall(WAF), which can detect and block injection attempts. An Intrusion Detection System(IDS) is another method of preventing attack. THis will monitor logs and alert developers if there is strange or unwanted code.