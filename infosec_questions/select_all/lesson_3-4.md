# Information Security MCQs — Lesson 3 & 4 (Select All That Apply)

Source: `lesson 3 & 4.pdf`

**Format:** Select ALL answers that apply (A-E).

**Mix:** Q1-Q125 are application/understanding-focused; Q126-Q150 are core knowledge checks.

---
## Q1. A web server allows directory listing and exposes config files. Which risks/controls apply?

- A) Information disclosure risk
- B) Disable directory listing
- C) Harden web server configuration
- D) Enable more directory browsing
- E) Publish config files intentionally

**Answer:** A, B, C

**Explanation:** Directory listing can expose sensitive files; disable it and harden configuration.

---

## Q2. A login form accepts unlimited attempts. Which mitigations help against dictionary attacks?

- A) Account lockout/throttling
- B) Strong password policy
- C) MFA
- D) Remove authentication
- E) Allow unlimited guesses

**Answer:** A, B, C

**Explanation:** Throttling, strong passwords, and MFA reduce guessing attack success.

---

## Q3. A user opens a macro-enabled attachment from unknown sender and malware runs. What applies?

- A) Macro virus risk
- B) User awareness/training needed
- C) Email filtering/attachment controls help
- D) Macros should always be enabled
- E) Unknown attachments are safe

**Answer:** A, B, C

**Explanation:** Macro malware is delivered via documents; training and filtering reduce risk.

---

## Q4. A program disguised as a useful tool installs a backdoor. Which statements are true?

- A) It is a Trojan horse
- B) It can create unauthorized access
- C) Software source trust matters
- D) It is harmless if filename looks normal
- E) It is the same as a web bug

**Answer:** A, B, C

**Explanation:** Trojans masquerade as legitimate software and can install backdoors.

---

## Q5. A compromised host is used to send spam and DDoS traffic. Which terms/controls apply?

- A) Zombie/bot
- B) Endpoint protection/monitoring
- C) Network egress monitoring
- D) Normal behavior
- E) Only a physical issue

**Answer:** A, B, C

**Explanation:** Compromised hosts can become bots; endpoint and egress monitoring help detect.

---

## Q6. A company finds hidden tracking pixels on its pages from third parties. Which apply?

- A) Web bugs/beacons
- B) Privacy concern
- C) Third-party content review needed
- D) Always improves security
- E) Same as firewall rules

**Answer:** A, B, C

**Explanation:** Web bugs can track users; third-party content should be reviewed.

---

## Q7. A site stores session token in a persistent cookie without secure flags. Risks include:

- A) Session theft/abuse
- B) Longer exposure window
- C) Need for secure cookie attributes
- D) Better security by default
- E) Eliminated CSRF risk automatically

**Answer:** A, B, C

**Explanation:** Insecure persistent cookies increase session risk.

---

## Q8. A user receives browser warning about invalid certificate on banking site. Appropriate actions?

- A) Do not enter credentials
- B) Verify URL/certificate through trusted channel
- C) Report suspected phishing
- D) Ignore warning and proceed
- E) Disable browser security

**Answer:** A, B, C

**Explanation:** Certificate warnings may indicate spoofing or misconfiguration.

---

## Q9. An attacker on public Wi-Fi captures unencrypted traffic. Which controls help?

- A) HTTPS/TLS
- B) VPN
- C) Avoid sensitive actions on open Wi-Fi
- D) Plain HTTP
- E) Disable encryption

**Answer:** A, B, C

**Explanation:** Encryption protects traffic from sniffing.

---

## Q10. A website is defaced after attacker exploits weak admin credentials. Which issues apply?

- A) Cybervandalism
- B) Weak authentication
- C) Need for hardening/monitoring
- D) Normal maintenance
- E) Only availability improvement

**Answer:** A, B, C

**Explanation:** Defacement is cybervandalism; weak auth and poor hardening contribute.

---

## Q11. An attacker sends packets with forged source IP. This is:

- A) Spoofing
- B) Can bypass weak trust controls
- C) Requires filtering/validation controls
- D) Same as backup
- E) Same as encryption

**Answer:** A, B, C

**Explanation:** Spoofing forges identity; filtering and authentication help.

---

## Q12. A DDoS flood overwhelms an e-commerce site. Which impacts/controls apply?

- A) Availability threat
- B) DDoS mitigation/rate limiting
- C) Capacity/resilience controls
- D) Only confidentiality issue
- E) Only integrity issue

**Answer:** A, B, C

**Explanation:** DoS affects availability; mitigation and resilience help.

---

## Q13. An employee connects to rogue Wi-Fi named like corporate SSID. Risks include:

- A) Traffic interception
- B) Credential theft
- C) Man-in-the-middle
- D) Guaranteed safety
- E) Stronger encryption automatically

**Answer:** A, B, C

**Explanation:** Rogue APs can intercept traffic and steal credentials.

---

## Q14. A company discovers wardriving attempts near office. Defenses include:

- A) Strong Wi-Fi encryption (WPA2/WPA3)
- B) Strong authentication/segmentation for wireless
- C) Monitoring for rogue APs
- D) Open Wi-Fi on corporate LAN
- E) Default SSID/password

**Answer:** A, B, C

**Explanation:** Strong wireless security, segmentation, and monitoring reduce risk.

---

## Q15. Sensitive file is emailed unencrypted. Which controls improve secrecy?

- A) Encryption
- B) Secure file sharing
- C) Data handling policy
- D) Post on public forum
- E) Use plaintext email

**Answer:** A, B, C

**Explanation:** Encryption and secure handling protect secrecy.

---

## Q16. Two systems exchange data using same shared secret key. Which are true?

- A) Symmetric encryption
- B) Key distribution is a challenge
- C) Efficient for bulk data
- D) Uses public/private key pair only
- E) No key needed

**Answer:** A, B, C

**Explanation:** Symmetric encryption uses one shared key and is efficient but key distribution can be challenging.

---

## Q17. A company uses public key to encrypt and private key to decrypt. Which are true?

- A) Asymmetric encryption
- B) Uses key pair
- C) Supports key exchange/signature use cases
- D) Same key used both ways
- E) No keys involved

**Answer:** A, B, C

**Explanation:** Asymmetric encryption uses public/private key pairs.

---

## Q18. A secure web session uses hybrid encryption. This means:

- A) Asymmetric for key exchange, symmetric for data
- B) Combines efficiency and secure key exchange
- C) Common in TLS/secure communications
- D) No encryption used
- E) Only hashing used

**Answer:** A, B, C

**Explanation:** Hybrid encryption combines symmetric and asymmetric strengths.

---

## Q19. An application crashes when long input overwrites memory. This is:

- A) Buffer overrun/overflow
- B) Input validation/coding flaw
- C) Potentially exploitable
- D) A cookie feature
- E) A normal firewall function

**Answer:** A, B, C

**Explanation:** Buffer overflows are coding flaws and may be exploitable.

---

## Q20. Thousands of emails flood an inbox making it unusable. This is:

- A) Mail bomb/DoS effect
- B) Availability issue
- C) Filtering/rate limiting can help
- D) Encryption at rest issue only
- E) Steganography

**Answer:** A, B, C

**Explanation:** Mail bombs affect availability; filtering helps.

---

## Q21. A firewall allows only required ports from internet to web server. This demonstrates:

- A) Least access/allowlisting
- B) Rule-based control
- C) Attack surface reduction
- D) Allow all inbound
- E) Default allow

**Answer:** A, B, C

**Explanation:** Restricting ports reduces attack surface.

---

## Q22. A firewall reviews source/destination IP and port before allowing packet. This is:

- A) Packet filtering
- B) Rule-based control
- C) Network boundary enforcement
- D) Steganography
- E) Data backup

**Answer:** A, B, C

**Explanation:** Packet filters inspect packet headers and apply rules.

---

## Q23. A gateway firewall blocks FTP because policy disallows it. This is:

- A) Application/protocol-aware filtering
- B) Policy enforcement
- C) Gateway firewall behavior
- D) Cookie management
- E) Disk encryption

**Answer:** A, B, C

**Explanation:** Gateway firewalls filter by application/protocol.

---

## Q24. A proxy firewall forwards web requests for internal users and hides internal addresses. Benefits:

- A) Address hiding/abstraction
- B) Centralized control/monitoring
- C) Policy enforcement
- D) Direct unrestricted exposure
- E) Removing authentication

**Answer:** A, B, C

**Explanation:** Proxies mediate requests and can enforce policy.

---

## Q25. Company enforces password complexity, MFA, and default password changes. This improves:

- A) Access control
- B) Resistance to guessing attacks
- C) Authentication strength
- D) Warchalking
- E) Steganography

**Answer:** A, B, C

**Explanation:** Strong auth controls reduce unauthorized access.

---

## Q26. Automatic patching is enabled on endpoints. Benefits include:

- A) Fix known vulnerabilities
- B) Reduce exploit window
- C) Improve security posture
- D) Guarantee no malware ever
- E) Eliminate need for backups

**Answer:** A, B, C

**Explanation:** Patching fixes known issues but not all threats.

---

## Q27. Users cannot install unapproved software. This helps:

- A) Reduce malware risk
- B) Standardize environment
- C) Support compliance/control
- D) Increase shadow IT safely
- E) Remove need for monitoring

**Answer:** A, B, C

**Explanation:** Software control reduces unmanaged risk.

---

## Q28. IDS/IPS detects abnormal packet flood and alerts/blocks. This supports:

- A) Detection
- B) Prevention/response
- C) Network protection
- D) Steganography
- E) Physical security only

**Answer:** A, B, C

**Explanation:** IDS/IPS support detection and prevention.

---

## Q29. Security awareness training teaches phishing recognition and reporting. This addresses:

- A) Human factor
- B) Insider/error risk
- C) Incident reporting
- D) Removing all technical controls
- E) Increasing click rates

**Answer:** A, B, C

**Explanation:** Training reduces human risk.

---

## Q30. Weekly full and daily incremental backups are implemented. This supports:

- A) Recovery
- B) Business continuity
- C) Data restoration after loss
- D) Preventing all incidents
- E) Replacing access control

**Answer:** A, B, C

**Explanation:** Backups support recovery, not incident prevention.

---

## Q31. A hidden message is embedded in an image sent over email. This is:

- A) Steganography
- B) Covert communication technique
- C) Different from plain encryption
- D) Packet filtering
- E) Firewalling

**Answer:** A, B, C

**Explanation:** Steganography hides data within other data.

---

## Q32. A digital certificate is used to verify a website. It helps with:

- A) Identity verification
- B) Trust establishment
- C) Secure communications/TLS
- D) Mail bombing
- E) Directory listing

**Answer:** A, B, C

**Explanation:** Certificates support identity and trust in secure communications.

---

## Q33. An attacker alters transaction amount in transit. Which controls help?

- A) Integrity controls/hashing/MAC
- B) TLS with integrity protection
- C) Digital signatures
- D) Directory listing
- E) Open HTTP

**Answer:** A, B, C

**Explanation:** Integrity mechanisms detect/prevent tampering.

---

## Q34. A sniffer captures credentials on unencrypted HTTP. Risks/mitigations:

- A) Confidentiality breach
- B) Use HTTPS/TLS
- C) Use VPN on untrusted networks
- D) Use telnet
- E) Use plaintext protocols

**Answer:** A, B, C

**Explanation:** Encrypt traffic to prevent sniffing.

---

## Q35. A company uses VPN for remote access. Benefits include:

- A) Encrypted tunnel over untrusted network
- B) Confidentiality/integrity protection
- C) Safer remote access
- D) No authentication needed
- E) No endpoint risk

**Answer:** A, B, C

**Explanation:** VPNs protect traffic; they still require authentication.

---

## Q36. A proxy firewall logs all outbound web requests. This supports:

- A) Monitoring
- B) Policy enforcement
- C) Incident investigation
- D) Hiding all user activity
- E) Disabling audits

**Answer:** A, B, C

**Explanation:** Proxy logs support monitoring and investigations.

---

## Q37. Gateway firewall blocks peer-to-peer app traffic per policy. This is:

- A) Application filtering
- B) Policy enforcement
- C) Attack surface/control management
- D) Steganography
- E) Encryption at rest

**Answer:** A, B, C

**Explanation:** Application-aware filtering enforces policy.

---

## Q38. Packet filter drops inbound traffic to unused ports. This is:

- A) Hardening/attack surface reduction
- B) Rule-based filtering
- C) Good firewall practice
- D) Allowing all services
- E) Default allow

**Answer:** A, B, C

**Explanation:** Closing unused ports reduces exposure.

---

## Q39. Strong password policy and lockout reduce:

- A) Brute force/dictionary attacks
- B) Unauthorized access risk
- C) Credential guessing success
- D) All phishing
- E) All malware

**Answer:** A, B, C

**Explanation:** They reduce guessing attacks but not all phishing.

---

## Q40. Input length checks and safe coding prevent:

- A) Buffer overflows
- B) Some crashes/exploits
- C) Memory corruption issues
- D) All vulnerabilities
- E) All social engineering

**Answer:** A, B, C

**Explanation:** Secure coding reduces overflow risk.

---

## Q41. Network segmentation separates guest Wi-Fi from corporate systems. Benefits:

- A) Limits lateral movement
- B) Reduces exposure of internal systems
- C) Containment
- D) Removes need for encryption
- E) Removes need for authentication

**Answer:** A, B, C

**Explanation:** Segmentation limits access and movement.

---

## Q42. User checks HTTPS lock and domain before login. This helps against:

- A) Phishing/spoofed sites
- B) Some interception risks
- C) Credential theft
- D) All malware
- E) All insider threats

**Answer:** A, B, C

**Explanation:** Verifying site identity reduces phishing risk.

---

## Q43. Stolen session cookie allows account takeover. Controls include:

- A) Secure/HttpOnly cookies
- B) TLS
- C) Session timeout/rebind
- D) Long-lived insecure cookies
- E) Plain HTTP

**Answer:** A, B, C

**Explanation:** Secure cookie handling reduces hijacking risk.

---

## Q44. Third-party persistent cookies track users across sites. Concerns:

- A) Privacy
- B) Cross-site tracking
- C) Data aggregation/profiling
- D) Improved confidentiality always
- E) Better availability

**Answer:** A, B, C

**Explanation:** Third-party cookies raise privacy concerns.

---

## Q45. Antivirus detects known malware signature. Limitations/roles:

- A) Detects known threats
- B) Needs updates
- C) Should be layered with other controls
- D) Catches all unknown threats perfectly
- E) Replaces patching

**Answer:** A, B, C

**Explanation:** AV is useful but not sufficient alone.

---

## Q46. Expired certificate on website causes browser warning. This means:

- A) Identity trust cannot be fully validated
- B) User should be cautious
- C) Certificate lifecycle management needed
- D) Site is automatically safe
- E) Encryption is impossible in all browsers forever

**Answer:** A, B, C

**Explanation:** Expired certs undermine trust.

---

## Q47. Malware arrives inside legitimate-looking installer. This involves:

- A) Trojan horse
- B) Social engineering/trust abuse
- C) Need for trusted sources/signatures
- D) Only network firewall issue
- E) Only physical security issue

**Answer:** A, B, C

**Explanation:** Trojans abuse trust; verify sources.

---

## Q48. Secure email gateway scans attachments/URLs. Benefits:

- A) Block known malicious content
- B) Reduce phishing/malware delivery
- C) Layered defense
- D) Eliminate user training need
- E) Guarantee no phishing

**Answer:** A, B, C

**Explanation:** Email gateways reduce but don't eliminate risk.

---

## Q49. Disabling directory listing on web server reduces:

- A) Information disclosure
- B) Reconnaissance help for attackers
- C) Exposure of sensitive files
- D) Need for authentication everywhere
- E) Need for TLS

**Answer:** A, B, C

**Explanation:** Directory listing can aid attackers.

---

## Q50. DNS spoofing redirects users to fake login page. Impacts/defenses:

- A) Credential theft risk
- B) Integrity/authenticity issue
- C) DNS security/HTTPS/cert validation help
- D) Only availability benefit
- E) Improved trust automatically

**Answer:** A, B, C

**Explanation:** Spoofing affects authenticity; cert validation helps.

---

## Q51. Layered controls include firewall, IDS, AV, backups, training. This is:

- A) Defense in depth
- B) Reduces single point of failure
- C) Comprehensive risk management
- D) One control only
- E) Security by obscurity

**Answer:** A, B, C

**Explanation:** Multiple controls provide layered defense.

---

## Q52. Encrypting laptop disks protects against:

- A) Data exposure from theft/loss
- B) Confidentiality breach if device stolen
- C) Unauthorized offline data access
- D) Phishing emails
- E) Network DDoS

**Answer:** A, B, C

**Explanation:** Disk encryption protects data at rest on lost devices.

---

## Q53. Web server requires auth and logs access. This provides:

- A) Access control
- B) Audit trail
- C) Detection/investigation support
- D) Guaranteed no breach
- E) No need for patching

**Answer:** A, B, C

**Explanation:** Auth and logs support control and accountability.

---

## Q54. Proxy firewall enforces acceptable use policy for web browsing. This supports:

- A) Policy enforcement
- B) Monitoring
- C) Risk reduction
- D) Complete anonymity for users
- E) No logs needed

**Answer:** A, B, C

**Explanation:** Proxies can enforce and monitor policy.

---

## Q55. Least privilege on file shares means:

- A) Users get only required access
- B) Limits breach impact
- C) Reduces accidental/malicious misuse
- D) Everyone gets write access
- E) No access reviews needed

**Answer:** A, B, C

**Explanation:** Least privilege limits exposure.

---

## Q56. Worm spreads through unpatched vulnerability. Mitigations:

- A) Patch management
- B) Network segmentation/firewall rules
- C) Endpoint detection
- D) Ignore vulnerability
- E) Disable all monitoring

**Answer:** A, B, C

**Explanation:** Patching and segmentation limit worm spread.

---

## Q57. Certificate warning on banking site. User should:

- A) Stop and verify
- B) Avoid entering credentials
- C) Use known-good URL/contact bank
- D) Bypass warning
- E) Disable TLS checks

**Answer:** A, B, C

**Explanation:** Treat cert warnings seriously.

---

## Q58. Offline backups help against ransomware because:

- A) Not directly reachable by malware
- B) Support recovery
- C) Improve resilience
- D) Prevent initial phishing
- E) Replace EDR

**Answer:** A, B, C

**Explanation:** Offline backups aid recovery but don't prevent phishing.

---

## Q59. HTTP traffic on open Wi-Fi is intercepted. Prevention:

- A) HTTPS/TLS
- B) VPN
- C) Avoid sensitive transactions on untrusted network
- D) Disable encryption
- E) Use HTTP only

**Answer:** A, B, C

**Explanation:** Use encrypted channels.

---

## Q60. Firewall log review reveals repeated blocked probes. This supports:

- A) Detection
- B) Threat awareness
- C) Incident response tuning
- D) Ignoring attacks
- E) Disabling firewall

**Answer:** A, B, C

**Explanation:** Logs provide detection and situational awareness.

---

## Q61. Single firewall at perimeter with no internal controls is risky because:

- A) No defense in depth
- B) Lateral movement easier after breach
- C) Single control failure impact high
- D) Perfect security
- E) No internal risk exists

**Answer:** A, B, C

**Explanation:** Layered internal controls are needed.

---

## Q62. Encryption, access control, and backups together address:

- A) Confidentiality
- B) Availability/recovery
- C) Multiple security objectives
- D) Only one objective
- E) No objective

**Answer:** A, B, C

**Explanation:** Different controls support different objectives.

---

## Q63. Credential stuffing succeeds after password reuse. Preventive controls:

- A) MFA
- B) Unique passwords/password manager
- C) Breach monitoring/rate limiting
- D) Password reuse
- E) Shared accounts

**Answer:** A, B, C

**Explanation:** MFA and unique passwords reduce credential stuffing.

---

## Q64. Backup restore test verifies:

- A) Recovery capability
- B) Backup integrity/usability
- C) RTO/RPO readiness insights
- D) That no backups are needed
- E) That backups never fail

**Answer:** A, B, C

**Explanation:** Testing confirms backups are usable.

---

## Q65. Social engineering leads to malware install. Defenses:

- A) User training
- B) Email/web filtering
- C) Endpoint protection/least privilege
- D) Blind trust
- E) Disabling reporting

**Answer:** A, B, C

**Explanation:** Human and technical controls reduce social engineering risk.

---

## Q66. Hardening includes:

- A) Removing default passwords
- B) Disabling unused services
- C) Applying secure configs/patches
- D) Enabling all services
- E) Keeping default credentials

**Answer:** A, B, C

**Explanation:** Hardening reduces attack surface through secure configuration.

---

## Q67. Digital signatures on software updates provide:

- A) Authenticity
- B) Integrity assurance
- C) Trust in source
- D) Encryption of all user data automatically
- E) Availability guarantee

**Answer:** A, B, C

**Explanation:** Signatures verify source and integrity.

---

## Q68. A company uses WAF, input validation, and parameterized queries. This is:

- A) Layered app security
- B) Injection risk reduction
- C) Defense in depth
- D) Single control
- E) No security

**Answer:** A, B, C

**Explanation:** Multiple app controls reduce injection risk.

---

## Q69. Unencrypted backup tapes lost in transit. Impacts/controls:

- A) Confidentiality breach risk
- B) Encrypt backups
- C) Secure transport/handling
- D) No risk
- E) Plaintext storage preferred

**Answer:** A, B, C

**Explanation:** Backups containing sensitive data should be encrypted and handled securely.

---

## Q70. An admin account is used daily for email and browsing. Risks/mitigations:

- A) High privilege exposure
- B) Use separate admin/user accounts
- C) Least privilege/MFA
- D) Best practice
- E) No risk

**Answer:** A, B, C

**Explanation:** Admins should use separate accounts and least privilege.

---

## Q71. Public-facing RDP exposed to internet. Risks/controls:

- A) Brute force/exploit risk
- B) Restrict access/VPN/MFA
- C) Patch and monitor
- D) Safe default
- E) No exposure risk

**Answer:** A, B, C

**Explanation:** Exposed RDP should be restricted and hardened.

---

## Q72. SIEM correlates firewall, endpoint, and auth logs. Benefits:

- A) Better detection
- B) Context for investigations
- C) Centralized visibility
- D) No need for logs
- E) Guaranteed prevention

**Answer:** A, B, C

**Explanation:** SIEM improves visibility and detection.

---

## Q73. A company enforces secure cookie flags (Secure, HttpOnly, SameSite). This helps:

- A) Reduce cookie theft/misuse
- B) Mitigate some web attacks
- C) Improve session security
- D) Make cookies public
- E) Disable HTTPS

**Answer:** A, B, C

**Explanation:** Secure cookie flags improve session protection.

---

## Q74. Unpatched legacy system cannot be replaced immediately. Compensating controls include:

- A) Network isolation
- B) Strict access controls/monitoring
- C) Virtual patching/WAF where applicable
- D) Expose to internet
- E) Remove all controls

**Answer:** A, B, C

**Explanation:** Compensating controls reduce legacy system risk.

---

## Q75. A company classifies incidents by severity and impact. This helps:

- A) Prioritize response
- B) Allocate resources
- C) Improve communication
- D) Ignore critical incidents
- E) Delay all response

**Answer:** A, B, C

**Explanation:** Severity classification supports effective response.

---

## Q76. Data in transit and at rest are encrypted, but keys are poorly managed. True statements:

- A) Key management is critical
- B) Poor key management can undermine encryption
- C) Keys need protection/rotation/processes
- D) Encryption is complete without key management
- E) Keys should be public

**Answer:** A, B, C

**Explanation:** Encryption depends on strong key management.

---

## Q77. A user receives MFA push they didn't initiate. They should:

- A) Deny/report it
- B) Treat as possible credential compromise
- C) Change password/follow policy
- D) Approve to stop prompts
- E) Ignore repeatedly

**Answer:** A, B, C

**Explanation:** Unexpected MFA prompts can indicate attack.

---

## Q78. A company uses allowlist for inbound firewall rules. Benefit:

- A) Only approved traffic allowed
- B) Reduced attack surface
- C) Clear policy enforcement
- D) All traffic allowed
- E) Default allow all

**Answer:** A, B, C

**Explanation:** Allowlisting restricts traffic to approved needs.

---

## Q79. A compromised certificate authority key would impact:

- A) Trust in issued certificates
- B) Identity verification
- C) Secure communications relying on those certs
- D) Nothing
- E) Only printer queues

**Answer:** A, B, C

**Explanation:** CA compromise undermines certificate trust.

---

## Q80. An organization implements DNS filtering and web proxy. This can:

- A) Block known malicious domains
- B) Enforce browsing policy
- C) Provide visibility/logging
- D) Replace endpoint security entirely
- E) Remove need for patching

**Answer:** A, B, C

**Explanation:** DNS filtering/proxy add control but not complete protection.

---

## Q81. A company requires code signing for internal scripts. This helps:

- A) Verify authenticity/integrity
- B) Reduce unauthorized script execution
- C) Improve trust in code
- D) Make scripts untraceable
- E) Disable auditing

**Answer:** A, B, C

**Explanation:** Code signing supports integrity and authenticity.

---

## Q82. An incident responder preserves memory, disk image, and logs. This supports:

- A) Forensic investigation
- B) Evidence integrity
- C) Root cause analysis
- D) Destroying evidence
- E) Tampering with evidence

**Answer:** A, B, C

**Explanation:** Preservation supports forensics.

---

## Q83. A company uses secure baseline images for servers. Benefits:

- A) Consistent hardening
- B) Faster secure deployment
- C) Reduced configuration drift
- D) More misconfigurations
- E) No auditing possible

**Answer:** A, B, C

**Explanation:** Baselines improve consistency and security.

---

## Q84. A rogue DHCP server appears on network. Risks/defenses:

- A) Traffic redirection/MITM risk
- B) Network monitoring/DHCP snooping
- C) Segmentation and controls
- D) No risk
- E) Improved trust automatically

**Answer:** A, B, C

**Explanation:** Rogue DHCP can redirect traffic; network controls help.

---

## Q85. A company deploys phishing-resistant MFA for admins. Benefits:

- A) Stronger authentication
- B) Reduced credential phishing impact
- C) Better privileged access protection
- D) No need for monitoring
- E) No need for least privilege

**Answer:** A, B, C

**Explanation:** Phishing-resistant MFA improves auth but monitoring still needed.

---

## Q86. Application logs show SQL errors after unusual input. This may indicate:

- A) SQL injection attempt
- B) Need for input validation/parameterized queries
- C) Need to investigate and block
- D) Normal harmless behavior always
- E) Successful hardening

**Answer:** A, B, C

**Explanation:** Suspicious errors can indicate injection attempts.

---

## Q87. A company uses egress filtering. This helps:

- A) Limit data exfiltration channels
- B) Detect/control unusual outbound traffic
- C) Enforce network policy
- D) Allow all outbound malware
- E) Disable monitoring

**Answer:** A, B, C

**Explanation:** Egress filtering restricts outbound traffic.

---

## Q88. A stolen laptop had unencrypted local database. Consequences include:

- A) Data confidentiality breach
- B) Regulatory/compliance impact
- C) Reputational damage
- D) No impact if password existed
- E) Guaranteed safety

**Answer:** A, B, C

**Explanation:** Unencrypted stolen data can cause breach and compliance issues.

---

## Q89. A company implements vulnerability disclosure program. Benefits:

- A) Receive reports from researchers
- B) Fix issues before exploitation
- C) Improve security posture
- D) Hide all vulnerabilities
- E) Ban security research

**Answer:** A, B, C

**Explanation:** Disclosure programs help identify and fix issues.

---

## Q90. TLS is configured but weak ciphers allowed. Risks/mitigations:

- A) Reduced confidentiality/integrity protection
- B) Update cipher configuration
- C) Follow modern TLS best practices
- D) Weak ciphers are preferred
- E) No action needed

**Answer:** A, B, C

**Explanation:** Weak crypto settings should be remediated.

---

## Q91. A firm uses PAM for privileged accounts. Benefits:

- A) Control/monitor privileged access
- B) Credential vaulting/rotation
- C) Reduced privilege misuse risk
- D) Shared admin passwords
- E) Unmonitored admin access

**Answer:** A, B, C

**Explanation:** PAM improves privileged access control.

---

## Q92. A company stores logs in write-once/tamper-evident storage. This supports:

- A) Log integrity
- B) Forensics
- C) Accountability
- D) Easy log tampering
- E) Log deletion by attackers

**Answer:** A, B, C

**Explanation:** Tamper-evident storage protects log integrity.

---

## Q93. A web app uses session timeout and re-authentication for sensitive actions. This reduces:

- A) Session hijacking impact
- B) Unauthorized use of unattended sessions
- C) Risk from stolen session
- D) All authentication needs
- E) Need for TLS

**Answer:** A, B, C

**Explanation:** Timeouts and re-auth reduce session abuse risk.

---

## Q94. A company applies security patches but does not test. Risks include:

- A) Service disruption/regressions
- B) Incomplete deployment
- C) Operational issues
- D) No risk at all
- E) Guaranteed stability

**Answer:** A, B, C

**Explanation:** Patch testing balances security and stability.

---

## Q95. A company monitors for data exfiltration patterns. This can detect:

- A) Unusual large transfers
- B) Suspicious destinations
- C) Possible compromise
- D) Guaranteed prevention
- E) No false negatives ever

**Answer:** A, B, C

**Explanation:** Monitoring can detect but not guarantee prevention.

---

## Q96. A mobile app stores API keys in client code. Risks:

- A) Key extraction
- B) Unauthorized API use
- C) Credential exposure
- D) Secure by design
- E) No impact

**Answer:** A, B, C

**Explanation:** Client-embedded secrets can be extracted.

---

## Q97. A company uses network access control (NAC). Benefits:

- A) Enforce device compliance before access
- B) Limit unauthorized devices
- C) Improve network security posture
- D) Allow any device unmanaged
- E) Remove authentication

**Answer:** A, B, C

**Explanation:** NAC controls device access based on policy.

---

## Q98. A firewall rule review finds overly permissive any-any rule. Actions:

- A) Remove/tighten rule
- B) Assess business need
- C) Document and monitor
- D) Keep it permanently
- E) Add more any-any rules

**Answer:** A, B, C

**Explanation:** Overly permissive rules should be tightened.

---

## Q99. A company trains developers on secure coding. This helps reduce:

- A) Common vulnerabilities
- B) Security bugs in production
- C) Remediation cost later
- D) All vulnerabilities forever
- E) Need for testing

**Answer:** A, B, C

**Explanation:** Secure coding training reduces common issues.

---

## Q100. A compromised third-party library is used in app. Controls include:

- A) SBOM/dependency management
- B) Vulnerability scanning
- C) Patch/update process
- D) Never updating dependencies
- E) Ignoring advisories

**Answer:** A, B, C

**Explanation:** Supply chain/dependency controls manage this risk.

---

## Q101. A company uses role separation between security, ops, and development. This supports:

- A) Segregation of duties
- B) Accountability
- C) Reduced fraud/error risk
- D) Single-person total control
- E) No audit trail

**Answer:** A, B, C

**Explanation:** Separation of duties improves control.

---

## Q102. An email account compromise is detected. Response includes:

- A) Reset credentials/revoke sessions
- B) Check forwarding rules/inbox abuse
- C) Investigate scope and notify as needed
- D) Ignore
- E) Keep compromised password

**Answer:** A, B, C

**Explanation:** Account compromise requires containment and investigation.

---

## Q103. A company requires VPN and endpoint compliance for remote admin. This provides:

- A) Controlled remote access
- B) Reduced exposure
- C) Better authentication and posture checks
- D) Unauthenticated admin access
- E) Direct internet exposure

**Answer:** A, B, C

**Explanation:** Remote admin should be tightly controlled.

---

## Q104. Sensitive data sent to wrong recipient by mistake. Controls to reduce recurrence:

- A) DLP and outbound checks
- B) User training
- C) Encryption/classification
- D) Remove all controls
- E) Encourage mass emailing

**Answer:** A, B, C

**Explanation:** Technical and administrative controls reduce accidental disclosure.

---

## Q105. A company finds its web app uses HTTP for login. Risks and fixes include:

- A) Credential sniffing
- B) Use HTTPS/TLS
- C) HSTS/secure redirects
- D) Keep HTTP for speed
- E) Disable encryption

**Answer:** A, B, C

**Explanation:** HTTP exposes credentials; TLS protects confidentiality/integrity.

---

## Q106. An attacker uses SQL injection through unvalidated input. Defenses include:

- A) Parameterized queries
- B) Input validation
- C) Least privilege DB account
- D) Directory listing
- E) Plaintext passwords

**Answer:** A, B, C

**Explanation:** Secure coding and least privilege reduce injection risk.

---

## Q107. A company deploys WPA3 and disables WPS on Wi-Fi. This helps against:

- A) Unauthorized wireless access
- B) Some Wi-Fi attacks
- C) Weak wireless configuration risk
- D) Mail bombs
- E) Buffer overflows

**Answer:** A, B, C

**Explanation:** Strong Wi-Fi config reduces unauthorized access.

---

## Q108. A phishing site uses valid-looking domain and stolen logo. Defenses include:

- A) User verification of URL/cert
- B) Anti-phishing filters
- C) MFA
- D) Ignoring browser warnings
- E) Disabling MFA

**Answer:** A, B, C

**Explanation:** Layered controls help detect and limit phishing.

---

## Q109. A file server has SMB exposed to internet. Risks/controls:

- A) Unauthorized access/exploitation
- B) Restrict exposure/firewall
- C) Patch and authenticate
- D) Expose all internal services
- E) Disable logging

**Answer:** A, B, C

**Explanation:** Internal services should not be unnecessarily exposed.

---

## Q110. A company uses certificate pinning in mobile app. Benefit:

- A) Reduces some MITM risk
- B) Validates expected certificate/public key
- C) Strengthens trust
- D) Disables encryption
- E) Removes server identity checks

**Answer:** A, B, C

**Explanation:** Pinning helps ensure app connects to expected server.

---

## Q111. A malware sample encrypts files and demands payment. Responses include:

- A) Isolate systems
- B) Restore from clean backups
- C) Report/investigate
- D) Immediately pay without analysis as only step
- E) Delete backups

**Answer:** A, B, C

**Explanation:** Containment, recovery, and investigation are key.

---

## Q112. A developer stores secrets in a managed vault instead of hardcoding. Benefits:

- A) Reduced exposure in code
- B) Easier rotation/management
- C) Better secret hygiene
- D) Publish secrets in repo
- E) Hardcode in client app

**Answer:** A, B, C

**Explanation:** Secrets should be managed outside source code.

---

## Q113. A company implements DMZ for public web servers. Benefits:

- A) Separates public-facing systems from internal network
- B) Limits breach impact
- C) Network segmentation
- D) Removes need for patching
- E) Removes need for monitoring

**Answer:** A, B, C

**Explanation:** DMZ provides segmentation and reduces internal exposure.

---

## Q114. A user receives unexpected password reset emails. This may indicate:

- A) Credential stuffing/phishing attempt
- B) Account targeting
- C) Need to verify account security/MFA
- D) Normal behavior to ignore always
- E) Guaranteed safety

**Answer:** A, B, C

**Explanation:** Unexpected resets can indicate account attack.

---

## Q115. A company uses HIDS and NIDS. Together they provide:

- A) Host and network visibility
- B) Better detection coverage
- C) Layered monitoring
- D) Guaranteed prevention
- E) No need for response

**Answer:** A, B, C

**Explanation:** HIDS/NIDS complement each other for detection.

---

## Q116. An attacker exploits outdated OpenSSL library. Mitigations:

- A) Patch/update dependencies
- B) Vulnerability scanning
- C) Asset/dependency inventory
- D) Ignore CVEs
- E) Disable patching

**Answer:** A, B, C

**Explanation:** Dependency management and patching reduce exposure.

---

## Q117. A company sets short session timeouts for banking app. This reduces:

- A) Session hijacking window
- B) Risk from unattended sessions
- C) Unauthorized use
- D) User authentication need entirely
- E) Need for TLS

**Answer:** A, B, C

**Explanation:** Timeouts limit session abuse opportunities.

---

## Q118. A web application uses Content Security Policy. This helps mitigate:

- A) Some XSS/content injection risks
- B) Unauthorized script sources
- C) Browser-side content control
- D) All server vulnerabilities
- E) All SQL injection

**Answer:** A, B, C

**Explanation:** CSP reduces some client-side injection risks.

---

## Q119. A company implements secure DNS (DNSSEC/filtered DNS). Benefits:

- A) Reduce DNS spoofing/tampering risk
- B) Improve trust in name resolution
- C) Block known malicious domains (filtered DNS)
- D) Replace all security controls
- E) Disable certificate validation

**Answer:** A, B, C

**Explanation:** Secure DNS improves resolution integrity and can block threats.

---

## Q120. A remote admin uses SSH keys instead of passwords. Benefits:

- A) Stronger authentication
- B) Reduced brute-force password risk
- C) Better access control when managed well
- D) No key management needed
- E) No auditing needed

**Answer:** A, B, C

**Explanation:** SSH keys improve auth but require key management.

---

## Q121. A company observes beaconing traffic to unknown domain. Actions:

- A) Investigate endpoint
- B) Block domain/IP as appropriate
- C) Contain and scope incident
- D) Ignore beaconing
- E) Disable monitoring

**Answer:** A, B, C

**Explanation:** Beaconing may indicate compromise; investigate and contain.

---

## Q122. A web server exposes detailed error messages. Risks/mitigations:

- A) Information disclosure
- B) Configure generic errors
- C) Log details server-side only
- D) Show stack traces to all users
- E) Expose debug info publicly

**Answer:** A, B, C

**Explanation:** Verbose errors aid attackers; keep details internal.

---

## Q123. A company uses mutual TLS for service-to-service auth. Benefits:

- A) Both parties authenticated
- B) Encrypted channel
- C) Stronger service identity trust
- D) No certificates needed
- E) No identity checks

**Answer:** A, B, C

**Explanation:** mTLS authenticates both client and server.

---

## Q124. A spam filter blocks malicious attachments. Limitations/roles:

- A) Reduces malware/phishing delivery
- B) Needs tuning/updates
- C) Part of layered defense
- D) Perfectly blocks all threats
- E) Replaces user training completely

**Answer:** A, B, C

**Explanation:** Filters help but are not perfect.

---

## Q125. An organization implements passwordless auth with FIDO2 keys. Benefits:

- A) Phishing resistance
- B) Strong authentication
- C) Reduced password risks
- D) No user verification ever
- E) No device management considerations

**Answer:** A, B, C

**Explanation:** FIDO2 provides strong, phishing-resistant auth.

---

## Q126. A dictionary attack involves:

- A) Trying common words/passwords from a list
- B) Encrypting files
- C) Filtering packets
- D) Backing up data
- E) Signing certificates

**Answer:** A

**Explanation:** Dictionary attacks use word lists to guess passwords.

---

## Q127. A macro virus is:

- A) Malware embedded in a macro within a file
- B) A firewall
- C) A certificate
- D) A VPN
- E) A proxy server

**Answer:** A

**Explanation:** Macro viruses execute through document macros.

---

## Q128. A Trojan horse:

- A) Masquerades as legitimate software
- B) Is always self-replicating
- C) Is a backup
- D) Is a certificate authority
- E) Is a packet filter

**Answer:** A

**Explanation:** Trojans disguise malicious functionality.

---

## Q129. A zombie/bot is:

- A) A compromised host used to attack others
- B) An offline backup
- C) A secure server
- D) An antivirus tool
- E) A firewall rule

**Answer:** A

**Explanation:** Zombies are compromised systems controlled by attackers.

---

## Q130. A web bug/beacon is:

- A) A small tracking object on a web page/email
- B) A SQL injection payload
- C) A firewall rule
- D) An encryption key
- E) A browser patch

**Answer:** A

**Explanation:** Web bugs track user activity.

---

## Q131. Session cookies:

- A) Expire when browser/session ends
- B) Last forever
- C) Are certificates
- D) Are firewalls
- E) Are backups

**Answer:** A

**Explanation:** Session cookies are temporary.

---

## Q132. Persistent cookies:

- A) Remain stored until expiration or deletion
- B) Expire immediately on close
- C) Are always malicious
- D) Encrypt traffic
- E) Replace authentication

**Answer:** A

**Explanation:** Persistent cookies remain across sessions.

---

## Q133. A digital certificate is issued by a:

- A) Certificate Authority (CA)
- B) ISP only
- C) End user only
- D) Firewall
- E) Sniffer

**Answer:** A

**Explanation:** CAs issue certificates.

---

## Q134. A sniffer is:

- A) A tool that captures network traffic
- B) A backup tool
- C) An encryption algorithm
- D) A firewall
- E) A certificate

**Answer:** A

**Explanation:** Sniffers capture packets.

---

## Q135. Cybervandalism is:

- A) Defacing/damaging digital property
- B) Encrypting backups
- C) Patching systems
- D) Using VPN
- E) Auditing logs

**Answer:** A

**Explanation:** Cybervandalism damages or defaces digital assets.

---

## Q136. Spoofing is:

- A) Falsifying identity/source
- B) Backing up data
- C) Normal authentication
- D) Encryption
- E) Logging

**Answer:** A

**Explanation:** Spoofing falsifies identity.

---

## Q137. A DoS attack aims to:

- A) Disrupt availability of service
- B) Improve performance
- C) Encrypt backups
- D) Issue certificates
- E) Validate integrity

**Answer:** A

**Explanation:** DoS targets availability.

---

## Q138. Wardriving is:

- A) Searching for Wi-Fi networks while moving
- B) Encrypting disks
- C) Patching servers
- D) Writing policies
- E) Filtering email

**Answer:** A

**Explanation:** Wardriving locates wireless networks.

---

## Q139. Warchalking is:

- A) Marking locations of Wi-Fi networks
- B) Driving to find Wi-Fi
- C) Firewall configuration
- D) Malware analysis
- E) Packet filtering

**Answer:** A

**Explanation:** Warchalking marks Wi-Fi locations.

---

## Q140. Symmetric encryption uses:

- A) The same key for encrypt/decrypt
- B) Two different keys
- C) No key
- D) Only public keys
- E) Only hashes

**Answer:** A

**Explanation:** Symmetric uses one shared key.

---

## Q141. Asymmetric encryption uses:

- A) A public/private key pair
- B) Same key only
- C) No keys
- D) Only cookies
- E) Only steganography

**Answer:** A

**Explanation:** Asymmetric uses key pairs.

---

## Q142. Hybrid encryption uses:

- A) Asymmetric for key exchange and symmetric for data
- B) Only one algorithm ever
- C) No encryption
- D) Only hashing
- E) Only steganography

**Answer:** A

**Explanation:** Hybrid combines both approaches.

---

## Q143. A buffer overrun occurs when:

- A) Data writes beyond allocated memory
- B) Disk is full
- C) Network is fast
- D) Cookie expires
- E) Certificate renews

**Answer:** A

**Explanation:** Buffer overruns overwrite memory.

---

## Q144. A mail bomb is:

- A) Flood of emails overwhelming a target
- B) Encrypted email
- C) Digital signature
- D) Backup email
- E) Training email

**Answer:** A

**Explanation:** Mail bombs overwhelm recipients/systems.

---

## Q145. A packet-filter firewall inspects:

- A) Packet headers against rules
- B) Only physical cables
- C) User training
- D) Backup tapes
- E) Screen content

**Answer:** A

**Explanation:** Packet filters inspect packet attributes.

---

## Q146. A proxy firewall:

- A) Makes requests on behalf of clients
- B) Only stores passwords
- C) Is an antivirus
- D) Is a web bug
- E) Is a worm

**Answer:** A

**Explanation:** Proxies intermediate requests.

---

## Q147. A gateway/application firewall filters by:

- A) Application/service/protocol
- B) Keyboard type
- C) Monitor size
- D) Backup schedule
- E) Mouse model

**Answer:** A

**Explanation:** Gateway firewalls filter by application/service.

---

## Q148. Steganography is:

- A) Hiding data within other data
- B) Encrypting with AES only
- C) Firewalling
- D) Patching
- E) Hashing

**Answer:** A

**Explanation:** Steganography conceals data.

---

## Q149. Antivirus software is used to:

- A) Detect/prevent/remove malware
- B) Create malware
- C) Replace all controls
- D) Open ports
- E) Issue certs

**Answer:** A

**Explanation:** Antivirus targets malware.

---

## Q150. RSA is an example of:

- A) Asymmetric encryption algorithm
- B) Symmetric algorithm
- C) Hash function only
- D) Firewall
- E) Protocol only

**Answer:** A

**Explanation:** RSA is asymmetric.

---

