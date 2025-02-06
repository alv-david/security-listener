# security-listener
Security Listener is a Python based Scanner that analyzes security misconfigurations about HTTP Headers, SSL Certificates, DNS and some common web vulnerabilities.


# main-features
DNS Bruteforcer: discover subdomains of an main web application - passive or aggressive scanning 
DNS analyzer: see DNS data based on public informations and enumerate possible vulnerabilities (like DNS poisoning and zone transfer)
HTTP Headers: enumerate which HTTP Headers are activated on the web application server


# vulnerability-enum
Security Listener has the power to enumerate the following vulnerabilities:
  Cross-site Scripting (XSS):
  
    1. Reflected XSS
    2. Stored XSS
    3. The script also has DOM-mining function, which attacks DOM parameters and points to the user where are some injection points.
    
  SQL Injection:
  
    In-band SQL Injection
      1. Error-based SQLi
      2. Union-based SQLi
    
    Blind SQLi
      1. Boolean-based SQLi
      2. Time-based SQLi
    
  Directory Enumeration:
  
    1. Dir Enumeration
    2. Path Traversal validation
