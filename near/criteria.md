# Wallet Security Criteria:

A wallet project must have a significant portion of these security program features in place, and shall self-certify that they maintain a security program that is commensurate (sufficiently similar) or better than the elements of the program outlined below. A project may also certify that they have a significant program in place, but intend to enhance the program to a level commensurate with the program outlined below by a given date.

Wallets shall checkbox a statement of compliance to be maintained on the wallet’s GitHub account or Website. The statement may qualitatively discuss the security program and include additional elements, or simply state that it is compliant with the program outlined below. When asserting that open items will be in place within some time period of being listed, target dates shall be included and clearly defined. The overall statement must be dated and the date shall be commensurate with the commit date. All wallet projects must maintain compliance while being included in the wallet listing/selector program. If a wallet is no longer in compliance, or no longer supported, the security statement must reflect that change and the wallet selector team shall be notified. The wallet project shall make verification of the following requirements as easy as possible--maximizing transparency through the use of relevant links pointing toward program descriptions, audit reports, etc. for the user/researcher.


1. Has a security program in place that covers or is dedicated to the wallet and...

2. Publishes information about its security program in an easily findable place.

3. Conducts regular audits of wallet code, at regular intervals of less than a year or based on meaningful code changes.

4. Conducts regular penetration tests, both “authenticated” and “non-authenticated” upon significant code changes.

5. Conducts penetration tests on related infrastructure, such as databases, virtual machines, web servers, etc.

6. Remediates any critical, high, or medium findings from audits (3, 4, an 5 above) in a rapid fashion, as suggested by auditors.  Auditors should validate the remediation in their reports.

7. Makes such reports (audits, penetration tests) publicly available, on at least a summary level.

8. When making reports (7) available, wallet projects should ensure the equivalent reports appear on the security vendor’s site or simply links to the security vendor’s report. This ensures the authenticity of the audit reports.

9. Conducts operational readiness reviews and testing or an equivalent process before deployment to production to ensure that code changes have not resulted in unanticipated behavior, compatibility issues, or inclusion of vulnerabilities.

10. Maintains a testnet wallet, available to developers and security researchers.

11. Implements minimal privilege and access policies with regard to supporting infrastructure.

12. Implements MFA and strong passwords for access to critical related systems, such as domain registration, hosting platforms, cloud platforms, etc.

13. Conducts known vulnerability and vulnerable dependency checks; and remediates critical, medium, and high findings before deploying to testnet or production.

14. If the wallet is a  browser “extension,” it is listed on the official extension marketplace.

15. Logs are collected from supporting infrastructure, web servers, etc.

16. Ensures that logs do not contain sensitive information, are encrypted at rest in storage, and have restricted access with least privilege.

17. Enables “audit logs” on related platforms (AWS, GCP, monitoring platforms, etc).

18. Logs shall be maintained for 90 days for forensic purposes.

19. Security feature shall be enabled in hosting environments, i.e. AWS GuardDuty.

20. Inputs shall be sanitized.

21. Code SAST scanning for vulnerabilities and vulnerable dependencies shall be conducted prior to production.

22. Vulnerability scanning shall be conducted regularly on websites, infrastructure-related VMs, etc.  Findings shall be quickly remediated.

23. Patch management shall be conducted frequently on supporting infrastructure.

24. VM and bare-metal infrastructure shall be protected by endpoint detection and response software.

25. An incident monitoring, alerting, and response program shall be in place.

26. Additional protective technologies, such as web application firewalls, should be put in place and appropriately configured to prevent attacks on the wallet.

27. White and black lists should be maintained for ip addresses and domains interacting with the wallet to the extent possible.

28. Access to infrastructure should be limited to VPNs or commensurate technology, IP restricted, etc. in order to prevent malicious access. For example, port 22 for the web server would not be accessible from the internet.

29. OWASP top 10 vulnerabilities shall be regularly tested and remediated.

30. Tools such as Nessus and Qualys, or similar should be used to scan for vulnerabilities.

31. Tools such as Burp Suite, or similar should be used to instrument and and analyze the interaction of the wallet with the browser for security issues.

32. Playbooks for public disclosure and communication to stakeholders and users should be prepared in advance and practiced via tabletop exercises in order to ensure rapid response and disclosure to protect such stakeholders and their assets.

33. An incident response retainer should be considered.

35. Wallet projects should clearly inform users of risks, risky behavior, best practices in the use of the wallet, and the most secure methods for using the wallet.

36. Wallet projects should have a clear path to reporting and receiving help on issues that is easily found by users.

37. Sensitive information should not be stored in the client-side wallet in a way that could be scraped from storage by malicious software, such as keys, recovery phrases, etc.

38. Encryption of sensitive data should likewise not rely on hard-coded keys or weak ciphers.

39. A user’s ability to recover their wallet under various circumstances should be clearly spelled out to the user when setting up the wallet.

40. Communication between infrastructure elements should be secured to the maximum extent possible.
    Please link to your the statement on your website or GitHub repo showing a statement of compliance. Please put link below (even if it is a placeholder).