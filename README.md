# Indodax Bug Bounty Program
Indodax recognises the importances of independent security groups or individual researchers in helping enhance our platform’s security and overall robustness. We encourage responsible disclosure of security vulnerabilities via our bug bounty program described in this page. 

## Rules
The following requirements must be adhered to in order to participate in Indodax’s bounty program :
- We investigate and respond to all valid reports. Due to the volume of reports we receive, though, we prioritise evaluations based on risk and other factors, and it may take some time before you receive a reply.
- We determine bounty amounts based on a variety of factors, including (but not limited to) impact, ease of exploitation, and quality of the report. Note that extremely low-risk issues may not qualify for a bounty at all.
- We seek to pay similar amounts for similar issues, but bounty amounts and qualifying issues may change with time. Past rewards do not necessarily guarantee similar results in the future.
- In the event of duplicate reports, we award a bounty to the first person to submit an issue. (Capacity determines duplicates and may not share details on the other reports.) A given bounty is only paid to one individual.
- Your participation in this program must not disrupt or compromise any data that does not belong to you. Any attacks against other users or company data without provable express consent are prohibited and will automatically disqualify you from participating in the program.
- You must not disclose the issue to the public or a third-party before it has been fixed and prior written consent from Indodax.
- You must comply with any applicable laws and regulations in connection with your participation in this program. 
- Indodax’s development team, employees and all other affiliates are not eligible for rewards.

Indodax’s bug bounty program is not a contest or competition. It is an experimental and discretionary rewards program. We may modify the terms of this program or terminate this program at any time without notice. All decisions as to the amount and type of rewards that may be issued, the method of payment (for monetary rewards), and whether or not any reported issue constitutes a significant risk or is eligible for a reward, will be determined at Indodax’s complete discretion in each case.

## Scope
The following domains are in the scope of the bug bounty program:
- Indodax.com and it subdomains.

Any design or implementation issue that substantially affects the confidentiality or integrity of user data is likely to be within the scope of the program, this include : 
```
- Cross-Site Request Forgery (CSRF).
- Reflective or stored XSS.
- Code Executions.
- SQL injections.
- Server Side Request Forgery (SSRF).
- Privilege Escalations.
- Authentication Bypasses.
- File inclusions (Local & Remote).
- Protection Mechanism bypasses (CSRF bypass, etc.).
- Leakage of sensitive informations.
- Directory Traversal.
- Open redirects which allow stealing tokens/secrets. 
```

## Out of Scope
In general, the following would not meet the threshold for severity:
```
- Any sort of DoS/DDoS attacks are strictly prohibited.
- Brute force attack.
- Social engineering, physical attack, phishing, spamming.
- Clickjacking.
- Application stack traces.
- Self-type Cross Site Scripting.
- CSRF with minimal security implications (Logout CSRF, etc.).
- Password complexity requirement.
- Rate Limit (i.e.: Email or SMS verification).
- Vulnerabilities in second party or third party applications or systems.
- Vulnerabilities affecting outdated or un-patched browsers or operating systems.
- Vulnerabilities requiring the user to be compromised or to have malicious browser extensions.
- Reports from automated tools or scans (without accompanying demonstration of exploitability).
```

## Rewards
- Indodax’s bounty program considers a number of variables in determining rewards (ie:  difficulty of execution, report quality, business impacts).
- All monetary rewards can only be credited to a Indodax wallet.
- You are solely responsible for any applicable taxes arising from or relating to your participation in the bug bounty program.
- Indodax will also issue certificate of recognition to distinguished individuals.

## Submission
Though we welcome reporting of non-security issues, please note that only genuine security issues are eligible for rewards. If you have found a vulnerability, we would love to work with you to resolve it:
- Please email us at itsec[at]indodax.com with the subject “[Bug Bounty Indodax] - Vulnerability Name”. Please do not contact employees directly or through other channels about a report.
- Within the body of the email, please describe the nature of the bug along with any steps required to replicate it, vulnerable component (API, FQDN, Deep URL), as well as pertinent applications, programs or tools used to discover the bug and the date and time testing took place.
- Include your legal name, phone number, and IP address at time of testing with your submission.

Please feel free to reach out to us at itsec[at]indodax.com with any questions regarding the bug bounty program. We receive a lot of submissions through this program, so we may not be able to reply to your email promptly, but we'll respond as soon as possible. We look forward to hearing from you.
