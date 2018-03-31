# Hacker Hour: Cyber Security
*"Alice, Bob, Eve and Trent"*

My Hacker Hour talk on Cyber Security - given at Rutgers University for USACS!

[Video](https://www.youtube.com/watch?v=ImMwbekDcYo)

## Topics Covered
- Authentication vs Identification vs Authentication
- Security Model (Alice, Bob, Eve and Trent)
    - Prevention, detection, recovery cycle
- Passwords
    - Salting Passwords
    - MS-CHAP protocol
- Man in the Middle Attacks
    - Using a signed message to prevent MITM Attack
    - Timestamps to prevent replay Attacks
- SSL Certificate/CA Overview
- Browser Security
    - What's possible?
- Cookies and XSRF in Browsers
    - How are XSRF attacks caused, possible damage
    - Using a `referrer` header in a cookie to defend against XSRF
- JWT (JSON Web Tokens) for authentication, encryption and signing
    - [Learn More about JWT](https://jwt.io/introduction)
- OAuth 2.0
- XSS attacks
    - Demo: [GAH](https://github.com/901/gah). Use the chat function and inject JS between <script> tags!
    - Defenses: OWASP Guidelines, Content Security Policy
    - [OWASP Guidelines](https://www.owasp.org/index.php/XSS_%28Cross_Site_Scripting%28_Prevention_Cheat_Sheet)
- SQL Injection
    - Demo: [Hackable](https://github.com/JasonHinds13/hackable)
    - Using prepared statements (parameterized values), database permissions and escape functions to avoid passing SQL Methods to execute.
