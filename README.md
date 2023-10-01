# Vulnerabilities discovered and reported
## ChatGPT (OpenAI) <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/ChatGPT_logo.svg/2048px-ChatGPT_logo.svg.png" alt="ChatGPT" width="25" height="25" />

###### A Cross-Site Scripting (XSS) vulnerability via Prompt Injection has been discovered in the OpenAI chat platform. An attacker can exploit this vulnerability to execute JavaScript code in a user's browser by causing the chatbot to interpret a Markdown syntax, resulting in the injection of a malicious hyperlink that redirects to document.cookie and allows the attacker to view the cookie in an alert.

**Reported and indexed by:**

[Packet Storm](https://packetstormsecurity.com/files/171665/chatgpt-xss.txt)

[Vulners](https://vulners.com/packetstorm/PACKETSTORM:171665)

[BugCrowd](https://bugcrowd.com/openai/hall-of-fame): Presence in the Bug Bounty Hall of Fame programme organised by OpenAI for discovering 6 vulnerabilities in ChatGPT and *.openai.com

## NASA <img src="https://www.nasa.gov/wp-content/themes/nasa/assets/images/nasa-logo.svg" alt="NASA" width="40" height="40" />

[BugCrowd](https://bugcrowd.com/nasa-vdp/hall-of-fame): Presence in the Bug Bounty Hall of Fame programme organised by National Aeronautics and Space Administration (NASA) - Vulnerability Disclosure Program for discovering 7 vulnerabilities in NASA and *.nasa.gov.

## Department of the Treasury <img src="https://logos.bugcrowdusercontent.com/logos/0fb2/c342/d858380d/869739581b872a8faa1aac2ea8c3ecf3_download__6_.png" alt="Departament Of The Treasury" width="40" height="40" />

[BugCrowd](https://bugcrowd.com/treasury-vdp/hall-of-fame): Presence in the Bug Bounty Hall of Fame programme organised by Department of the Treasury: Vulnerability Disclosure Program for discovering 4 vulnerabilities.

## Flask-AppBuilder <img src="https://play-lh.googleusercontent.com/keVVojxW-b11NTKWZg8GulfLlhqBpATvqGFViblYsI0fxW_8a0sIPgyRlB94Gu1AQMY" alt="Flask-AppBuilder" width="40" height="40" />

###### An authenticated malicious actor with Admin privileges, could by adding a special character on the add, edit User forms trigger a database error, this error is surfaced back to this actor on the UI. On certain database engines this error can include the entire user row including the pbkdf2:sha256 hashed password.

https://github.com/dpgaspar/Flask-AppBuilder/security/advisories/GHSA-jhpr-j7cq-3jp3

#### CVE-2023-34110

https://nvd.nist.gov/vuln/detail/CVE-2023-34110

https://www.incibe.es/incibe-cert/alerta-temprana/vulnerabilidades/cve-2023-34110

https://vuldb.com/es/?id.232202

## Chamilo LMS <img src="https://play-lh.googleusercontent.com/Yk_tVHx3pqtUpwzh4dCZhqJ9bt1HYbxTz99mDxjtwJ0P50Z7A9G-BTjv_zNK1ExnKqGA" alt="Chamilo LMS" width="45" height="45" />

###### Chamilo 1.11.x allows a user to add XSS to his/her own profile on the social network. If the "skype" and "linkedin_url" fields are enabled (they are by default) or if other text-type fields are added, these can be used by a user to target other users looking at his/her profile on the social network. This requires befriending the attacker first or viewing the profile as an administrator (so it could be used to XSS the admin). It requires a normal user account, so not available to anonymous users.

###### Reported by: Miguel Segovia

###### Fix for Chamilo 1.11.*: https://github.com/chamilo/chamilo-lms/commit/4a587707b0b88954eaf4a607bb1a908279c6072c

**Reported and indexed by:**

- CVE-2023-31799
- CVE-2023-31800
- CVE-2023-31801
- CVE-2023-31802
- CVE-2023-31803
- CVE-2023-31804
- CVE-2023-31805
- CVE-2023-31806
- CVE-2023-31807

[Chamilo Issue "#104" - 2023-04-11 - Moderate impact, High risk - XSS in personal profile ](https://support.chamilo.org/projects/chamilo-18/wiki/Security_issues#Issue-104-2023-04-11-Moderate-impact-High-risk-XSS-in-personal-profile)

[Chamilo Issue "#103" - 2023-04-11 - Low impact, Moderate risk - XSS in "My progress" tab](https://support.chamilo.org/projects/chamilo-18/wiki/Security_issues#Issue-103-2023-04-11-Low-impact-Moderate-risk-XSS-in-My-progress-tab)

[Chamilo Issue "#102" - 2023-04-11 - Low impact, Moderate risk - XSS in forum titles](https://support.chamilo.org/projects/chamilo-18/wiki/Security_issues#Issue-102-2023-04-11-Low-impact-Moderate-risk-XSS-in-forum-titles)

[Chamilo Issue "#101" - 2023-04-11 - Low impact, Low risk - XSS in personal notes and teacher notes](https://support.chamilo.org/projects/chamilo-18/wiki/Security_issues#Issue-101-2023-04-11-Low-impact-Low-risk-XSS-in-personal-notes-and-teacher-notes)

[Chamilo Issue "#100" - 2023-04-11 - Low impact, Low risk - XSS in resources sequencing](https://support.chamilo.org/projects/chamilo-18/wiki/Security_issues#Issue-100-2023-04-11-Low-impact-Low-risk-XSS-in-resources-sequencing)

[Chamilo Issue "#99" - 2023-04-11 - Low impact, Low risk - XSS in system announcements](https://support.chamilo.org/projects/chamilo-18/wiki/Security_issues#Issue-99-2023-04-11-Low-impact-Low-risk-XSS-in-system-announcements)

[Chamilo Issue "#98" - 2023-04-11 - Low impact, Low risk - XSS in homepage edition](https://support.chamilo.org/projects/chamilo-18/wiki/Security_issues#Issue-98-2023-04-11-Low-impact-Low-risk-XSS-in-homepage-edition)

[Chamilo Issue "#97" - 2023-04-11 - Low impact, High risk - XSS in skills wheel](https://support.chamilo.org/projects/chamilo-18/wiki/Security_issues#Issue-97-2023-04-11-Low-impact-High-risk-XSS-in-skills-wheel)

[Chamilo Issue "#96" - 2023-04-06 - Low impact, Moderate risk - XSS in course categories](https://support.chamilo.org/projects/chamilo-18/wiki/Security_issues#Issue-96-2023-04-06-Low-impact-Moderate-risk-XSS-in-course-categories)

