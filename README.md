# Vulnerabilities discovered and reported
## ChatGPT (OpenAI)

###### A reflected Cross-Site Scripting (XSS) vulnerability has been discovered in the OpenAI chat platform. An attacker can exploit this vulnerability to execute JavaScript code in a user's browser by causing the chatbot to interpret a Markdown syntax, resulting in the injection of a malicious hyperlink that redirects to document.cookie and allows the attacker to view the cookie in an alert.

**Reported and indexed by:**

[Packet Storm](https://packetstormsecurity.com/files/171665/chatgpt-xss.txt)

[Vulners](https://vulners.com/packetstorm/PACKETSTORM:171665)
