# THREATS-VS-VULNERABILITIES

Many people think a threat and a vulnerability are the same thing, but they are different. In this lab I explain the difference and give 10 examples.

## Definitions

| Term | Meaning | Simple example |
|---|---|---|
| Threat | Something that can cause harm to a system. It can be a person, an event or a situation. | A thief. He is the danger. |
| Vulnerability | A weak point in a system. A threat can use it to do harm. | A door that is not locked. It is the weak point. |

**How they work together.** A threat needs a weak point to attack. If the system has no weak point, the threat cannot do much. If there is a weak point but nobody attacks it, there is no problem. The risk starts when the threat finds the weak point. For example, a thief is not dangerous to a house with a locked door, but he is dangerous if the door is open.

**My simple check.** To check, I ask myself, is this a weak point, or is it something that can attack the weak point? If it is a weak point, it is a vulnerability. If it can attack, it is a threat.

## Examples

| No | Situation | Type | Reason |
|---|---|---|---|
| 1 | A student gets an SMS from a fake bank. It says the account is locked and asks the student to click a link. | Threat | It is phishing. Someone is trying to steal the student's login. |
| 2 | A computer in the lab still uses Windows 7. It does not get security updates now. | Vulnerability | The old system has problems and nobody will fix them. |
| 3 | An office router still uses the default password "admin". | Vulnerability | The password is easy to guess, so it is a weak setting. |
| 4 | Attackers use many computers to send too much traffic to a university website. The website stops working. | Threat | It is a DDoS attack. The website is not available for users. |
| 5 | A developer puts a database password on a public GitHub repo by mistake. | Vulnerability | Anyone can see the password. It happened because of human error. |
| 6 | A staff member copies student data to a USB drive to sell it. | Threat | It is an insider threat. He can access the data, but he uses it in a bad way. |
| 7 | A website login form does not check what the user types. | Vulnerability | It is a coding problem. Hackers can use SQL injection. |
| 8 | Criminals send a fake invoice by email. Inside the file there is ransomware. | Threat | Ransomware locks the files and asks for money. It is a direct attack. |
| 9 | An employee uses "12345" as a password and there is no multi-factor authentication. | Vulnerability | The password is very weak, so hackers can guess it easily. |
| 10 | Scammers put fake job ads on social media to get people's personal information. | Threat | It is social engineering. They trick people, not the computer. |
