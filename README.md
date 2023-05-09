# Vulnerabilities discovered and reported
## ChatGPT (OpenAI) <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/ChatGPT_logo.svg/2048px-ChatGPT_logo.svg.png" alt="Texto alternativo" width="25" height="25" />

###### A Cross-Site Scripting (XSS) vulnerability via Prompt Injection has been discovered in the OpenAI chat platform. An attacker can exploit this vulnerability to execute JavaScript code in a user's browser by causing the chatbot to interpret a Markdown syntax, resulting in the injection of a malicious hyperlink that redirects to document.cookie and allows the attacker to view the cookie in an alert.

**Reported and indexed by:**

[Packet Storm](https://packetstormsecurity.com/files/171665/chatgpt-xss.txt)

[Vulners](https://vulners.com/packetstorm/PACKETSTORM:171665)

[BugCrowd](https://bugcrowd.com/openai/hall-of-fame): Presence in the Bug Bounty Hall of Fame programme organised by OpenAI for discovering 4 vulnerabilities in ChatGPT and *.openai.com

## Chamilo LMS <img src="https://play-lh.googleusercontent.com/Yk_tVHx3pqtUpwzh4dCZhqJ9bt1HYbxTz99mDxjtwJ0P50Z7A9G-BTjv_zNK1ExnKqGA" alt="Texto alternativo" width="45" height="45" />

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

