## Case 02 - URL Shortening Suspicious Sender

### Alert Information
<img width="719" height="359" alt="Screenshot 2026-09-17 095210" src="https://github.com/user-attachments/assets/14d2ab51-f60f-4e00-8b3c-ae70751fe2eb" />
**List of affected entities:** <br>
Recipient: `h.harris@thetrydaily.thm` <br>
IP: `10.20.2.17` <br>
Host: `win-3457`
<br>
**List of attack indicators:** <br>
Sender: `urgents@amazon.biz` <br>
URL: `http://bit.ly/3sHkX3da12340`
Destination IP: `67.199.248.11`

### Investigation & Analysis
The alert indicated that `urgents@amazon.biz` sent an email to `h.harris@thetrydaily.thm` regarding an incomplete shipping address that needed to be filled out and the message appeared to be urgent, at 09/17/2026 03:47. The email contained a suspicious URL shortener: `http://bit.ly/3sHkX3da12340`, with the intent of getting `h.harris@thetrydaily.thm` to open the URL.

The URL was analyzed using TryDetectThis and flagged as MALICIOUS.
<img width="652" height="274" alt="Screenshot 2026-09-17 095538" src="https://github.com/user-attachments/assets/cec31998-4e47-4cc0-ab2f-69f27d00d914" />

It was also discovered that the URL leads to an unknown IP address: 67.199.248.11, which was also flagged as MALICIOUS.
<img width="654" height="271" alt="Screenshot 2026-09-17 095605" src="https://github.com/user-attachments/assets/8d2b73fc-de77-4337-a4cf-dc2513ac49e6" />

This activity potentially indicates a phishing email and a malicious URL related to Spearphishing Link T1598.003 in MITRE ATTACK.

### Classification & Escalation
| Classification     | Escalation          |
|--------------------|---------------------|
| True Positive (TP) | Escalation is needed for further investigation |

### Final Asessment


### Remediation Recommendations
