# Information Security MCQs — Lesson 1 & 2 (Select All That Apply)

Source: `lesson 1-2.pdf`

**Format:** Select ALL answers that apply (A-E).

**Mix:** Q1-Q125 are application/understanding-focused; Q126-Q150 are core knowledge checks.

---
## Q1. A hospital encrypts patient records, restricts access by role, and keeps audit logs. Which security objectives/controls are being supported?

- A) Confidentiality
- B) Access control
- C) Accountability
- D) Availability only
- E) Risk avoidance only

**Answer:** A, B, C

**Explanation:** Encryption supports confidentiality, role restrictions support access control, and logs support accountability.

---

## Q2. An attacker modifies a prescription record in transit. Which security goals are most directly threatened?

- A) Integrity
- B) Authenticity/trust in data
- C) Availability
- D) Non-repudiation of the legitimate sender only
- E) Physical security

**Answer:** A, B

**Explanation:** Unauthorized modification threatens integrity and trust in the data.

---

## Q3. A company wants to prevent staff from denying they approved a wire transfer. Which controls/mechanisms help?

- A) Digital signatures
- B) Audit logging
- C) Non-repudiation controls
- D) Disabling authentication
- E) Shared accounts

**Answer:** A, B, C

**Explanation:** Digital signatures and audit logs support non-repudiation.

---

## Q4. A ransomware attack encrypts file servers and halts operations. Which impacts may apply?

- A) Availability loss
- B) Potential integrity concerns
- C) Possible confidentiality exposure if data was exfiltrated
- D) No security impact if backups exist
- E) Improved authentication

**Answer:** A, B, C

**Explanation:** Ransomware primarily affects availability but may also involve integrity/confidentiality impacts.

---

## Q5. A startup stores customer data in plaintext on a public bucket. Which security failures are present?

- A) Confidentiality failure
- B) Poor access control
- C) Increased exposure risk
- D) Strong defense in depth
- E) Proper data minimization

**Answer:** A, B, C

**Explanation:** Public plaintext storage exposes data and indicates weak access control.

---

## Q6. An organization implements MFA, least privilege, and security awareness. What risks are reduced?

- A) Credential compromise impact
- B) Unauthorized access
- C) Social engineering success likelihood
- D) All security risk to zero
- E) Need for monitoring

**Answer:** A, B, C

**Explanation:** These controls reduce risk but cannot eliminate all risk.

---

## Q7. A disgruntled admin deletes critical logs and changes configurations. Which insider threat characteristics apply?

- A) Misuse of legitimate access
- B) Potential integrity impact
- C) Potential availability impact
- D) External-only threat
- E) Passive attack only

**Answer:** A, B, C

**Explanation:** Insiders can misuse legitimate access and affect integrity/availability.

---

## Q8. A company classifies data as public, internal, confidential, and restricted. This supports:

- A) Appropriate handling
- B) Risk-based controls
- C) Access decisions
- D) Eliminating all breaches
- E) Replacing encryption

**Answer:** A, B, C

**Explanation:** Classification guides handling, controls, and access.

---

## Q9. During incident response, a team isolates affected systems, preserves evidence, and notifies stakeholders. These actions support:

- A) Containment
- B) Forensics/investigation
- C) Communication/management
- D) Ignoring the incident
- E) Deleting evidence

**Answer:** A, B, C

**Explanation:** Containment, evidence preservation, and communication are key IR actions.

---

## Q10. A web application validates input, uses parameterized queries, and enforces least privilege DB accounts. Which risks are mitigated?

- A) SQL injection
- B) Excessive DB damage from compromise
- C) Input-based abuse
- D) All network attacks
- E) Physical theft

**Answer:** A, B, C

**Explanation:** These mitigate injection and limit impact.

---

## Q11. A company uses backups, UPS, and redundant servers. Which goals are primarily supported?

- A) Availability
- B) Resilience
- C) Recovery capability
- D) Confidentiality only
- E) Non-repudiation only

**Answer:** A, B, C

**Explanation:** These controls support availability and resilience.

---

## Q12. An employee leaves a laptop unencrypted in a car and it is stolen. Which controls would have reduced impact?

- A) Full disk encryption
- B) Strong authentication
- C) Remote wipe capability
- D) Directory listing
- E) Open guest Wi-Fi

**Answer:** A, B, C

**Explanation:** Encryption, authentication, and remote wipe reduce stolen-device impact.

---

## Q13. A security policy requires patching, vulnerability scanning, and change management. These help manage:

- A) Known vulnerabilities
- B) Configuration risk
- C) Operational changes
- D) All zero-day exploits completely
- E) Physical access only

**Answer:** A, B, C

**Explanation:** They reduce known vulnerability/configuration/change risk but not all zero-days.

---

## Q14. A phishing email tricks a user into revealing credentials. Which controls could help prevent or limit this?

- A) User awareness training
- B) MFA
- C) Email filtering
- D) Disabling all business email permanently
- E) Shared passwords

**Answer:** A, B, C

**Explanation:** Training, MFA, and filtering help reduce phishing risk.

---

## Q15. A company performs risk assessment and finds a critical unpatched server. Appropriate responses may include:

- A) Patch promptly
- B) Apply compensating controls if patch delayed
- C) Document risk decision
- D) Ignore because it's internal
- E) Expose it publicly for testing

**Answer:** A, B, C

**Explanation:** Patching, compensating controls, and documented decisions are appropriate.

---

## Q16. A database admin can modify data, approve changes, and delete logs. What governance issue exists?

- A) Lack of segregation of duties
- B) Excessive privilege
- C) Accountability weakness
- D) Strong control design
- E) Proper least privilege

**Answer:** A, B, C

**Explanation:** Combining incompatible duties creates control weakness.

---

## Q17. A company adopts defense in depth for its web app. Which layers could be included?

- A) WAF/firewall
- B) Secure coding/input validation
- C) Monitoring/logging
- D) Single password only
- E) No patching

**Answer:** A, B, C

**Explanation:** Defense in depth uses multiple layers.

---

## Q18. An organization discovers sensitive data exfiltration. Which immediate actions are appropriate?

- A) Contain the exfiltration path
- B) Assess scope/impact
- C) Preserve evidence
- D) Publicly post all forensic details immediately
- E) Delete logs

**Answer:** A, B, C

**Explanation:** Containment, scoping, and evidence preservation are appropriate.

---

## Q19. A secure authentication system should include:

- A) Strong credential policies or MFA
- B) Account lockout/throttling
- C) Logging/monitoring
- D) Shared admin passwords
- E) Unencrypted password storage

**Answer:** A, B, C

**Explanation:** Good authentication includes strong controls, throttling, and monitoring.

---

## Q20. A company uses encryption in transit and at rest. This primarily helps with:

- A) Confidentiality
- B) Protection against interception/theft exposure
- C) Data protection on lost devices
- D) Guaranteed availability
- E) Eliminating all integrity risks

**Answer:** A, B, C

**Explanation:** Encryption protects confidentiality; it does not guarantee availability.

---

## Q21. A system compromise occurred due to weak password and no MFA. Which lessons apply?

- A) Authentication controls matter
- B) Layered defenses reduce risk
- C) Single control failure can be critical
- D) Passwords alone are always sufficient
- E) MFA is unnecessary

**Answer:** A, B, C

**Explanation:** Weak single-factor auth increases risk.

---

## Q22. A security team implements logging, SIEM alerts, and incident playbooks. This improves:

- A) Detection
- B) Response readiness
- C) Operational consistency
- D) Guaranteed zero incidents
- E) No need for training

**Answer:** A, B, C

**Explanation:** These improve detection and response but cannot guarantee zero incidents.

---

## Q23. A company allows BYOD without controls. Risks include:

- A) Data leakage
- B) Unmanaged device vulnerabilities
- C) Loss/theft exposure
- D) Perfect endpoint security
- E) Reduced compliance burden automatically

**Answer:** A, B, C

**Explanation:** Unmanaged BYOD increases risk.

---

## Q24. A critical service has no redundancy and no backup. Which risks are high?

- A) Availability loss
- B) Prolonged recovery
- C) Business disruption
- D) Improved resilience
- E) Strong continuity

**Answer:** A, B, C

**Explanation:** Lack of redundancy/backups harms availability and recovery.

---

## Q25. A company enforces change management for firewall rules. Benefits include:

- A) Reduced misconfiguration
- B) Auditability
- C) Controlled changes
- D) No need for review
- E) Untracked emergency changes as default

**Answer:** A, B, C

**Explanation:** Change management improves control and accountability.

---

## Q26. An attacker gains access through an unpatched VPN appliance. Which preventive measures apply?

- A) Timely patching
- B) Vulnerability management
- C) Exposure reduction/asset inventory
- D) Ignoring vendor advisories
- E) Disabling monitoring

**Answer:** A, B, C

**Explanation:** Patch/vulnerability management and inventory reduce exposure.

---

## Q27. A company stores logs securely and reviews them regularly. This supports:

- A) Detection
- B) Accountability
- C) Investigation
- D) Eliminating all attacks
- E) Replacing all preventive controls

**Answer:** A, B, C

**Explanation:** Logs support detection, accountability, and investigation.

---

## Q28. A data breach report must be clear and useful. It should include:

- A) What happened/scope
- B) Impact and affected assets/data
- C) Response/remediation actions
- D) Only rumors
- E) Unverified assumptions only

**Answer:** A, B, C

**Explanation:** Good reporting includes scope, impact, and actions.

---

## Q29. A developer hardcodes credentials in source code. Risks include:

- A) Credential exposure
- B) Unauthorized access
- C) Difficult rotation
- D) Improved security
- E) Easier compliance

**Answer:** A, B, C

**Explanation:** Hardcoded credentials are a security risk.

---

## Q30. A company uses least privilege for service accounts. This helps:

- A) Limit blast radius
- B) Reduce unauthorized actions
- C) Support defense in depth
- D) Give every process admin rights
- E) Remove need for monitoring

**Answer:** A, B, C

**Explanation:** Least privilege limits impact and unauthorized actions.

---

## Q31. A user reports a suspicious USB drive found in parking lot. Proper actions include:

- A) Do not plug it in
- B) Report to security/IT
- C) Follow incident policy
- D) Test it on production workstation
- E) Share it with coworkers to try

**Answer:** A, B, C

**Explanation:** Unknown media should be handled per policy.

---

## Q32. A company implements network segmentation between user, server, and management networks. This can:

- A) Limit lateral movement
- B) Contain breaches
- C) Protect critical systems
- D) Remove need for authentication
- E) Eliminate patching

**Answer:** A, B, C

**Explanation:** Segmentation limits movement but does not remove auth needs.

---

## Q33. A security awareness program should cover:

- A) Phishing/social engineering
- B) Password/MFA hygiene
- C) Incident reporting
- D) How to bypass controls
- E) Sharing credentials

**Answer:** A, B, C

**Explanation:** Awareness should cover common threats and reporting.

---

## Q34. An organization uses secure configuration baselines. Benefits include:

- A) Consistency
- B) Reduced misconfiguration
- C) Easier auditing
- D) Guaranteed no vulnerabilities
- E) No need for updates

**Answer:** A, B, C

**Explanation:** Baselines improve consistency and reduce misconfigurations.

---

## Q35. A company evaluates third-party vendor security before integration. This addresses:

- A) Supply chain risk
- B) Third-party access risk
- C) Due diligence
- D) Eliminating all vendor risk
- E) Removing contracts

**Answer:** A, B, C

**Explanation:** Vendor assessment reduces but does not eliminate third-party risk.

---

## Q36. A critical system requires high availability. Which designs help?

- A) Redundancy/failover
- B) Backups and tested recovery
- C) Monitoring and alerting
- D) Single point of failure
- E) No maintenance windows ever

**Answer:** A, B, C

**Explanation:** Redundancy, recovery, and monitoring support availability.

---

## Q37. A security incident postmortem should produce:

- A) Root cause understanding
- B) Lessons learned
- C) Remediation/improvement actions
- D) Blame only, no fixes
- E) Deleted evidence

**Answer:** A, B, C

**Explanation:** Postmortems should drive learning and improvement.

---

## Q38. An organization applies data minimization and retention limits. This helps with:

- A) Privacy risk reduction
- B) Reduced breach impact
- C) Compliance
- D) Collecting all possible data forever
- E) Unlimited retention

**Answer:** A, B, C

**Explanation:** Minimization and retention limits reduce exposure.

---

## Q39. A company uses role-based access control. Advantages include:

- A) Easier permission management
- B) Consistency with job roles
- C) Support for least privilege
- D) Everyone gets admin
- E) No access reviews needed

**Answer:** A, B, C

**Explanation:** RBAC supports manageable, role-aligned access.

---

## Q40. A web server is exposed with default credentials and open admin interface. Risks include:

- A) Unauthorized access
- B) System compromise
- C) Data breach
- D) Strong security posture
- E) Reduced attack surface

**Answer:** A, B, C

**Explanation:** Defaults and exposed admin interfaces are serious risks.

---

## Q41. A company implements secure backup strategy. It should include:

- A) Regular backups
- B) Offsite/offline or protected copies
- C) Restore testing
- D) Never testing restores
- E) Storing only on same server

**Answer:** A, B, C

**Explanation:** Backups must be regular, protected, and tested.

---

## Q42. An attacker uses stolen credentials to access cloud console. Which controls help?

- A) MFA
- B) Conditional access/anomaly detection
- C) Least privilege roles
- D) Shared credentials
- E) Disabled logging

**Answer:** A, B, C

**Explanation:** MFA, conditional access, and least privilege reduce impact.

---

## Q43. A company encrypts sensitive emails and trains staff on handling. This addresses:

- A) Confidentiality
- B) Human error risk
- C) Policy compliance
- D) Availability only
- E) Physical redundancy only

**Answer:** A, B, C

**Explanation:** Encryption and training support confidentiality and compliance.

---

## Q44. A vulnerability scan reports critical findings. Good next steps include:

- A) Validate/prioritize findings
- B) Remediate or mitigate based on risk
- C) Track to closure
- D) Ignore all reports
- E) Delete scan results

**Answer:** A, B, C

**Explanation:** Findings should be triaged, remediated, and tracked.

---

## Q45. A company adopts secure SDLC practices. This may include:

- A) Threat modeling
- B) Code review/security testing
- C) Patch/update process
- D) Skipping security until release
- E) No change control

**Answer:** A, B, C

**Explanation:** Secure SDLC integrates security throughout development.

---

## Q46. An organization handles PII. Appropriate controls include:

- A) Access restrictions
- B) Encryption where appropriate
- C) Logging and policy controls
- D) Public posting for transparency
- E) Unrestricted sharing

**Answer:** A, B, C

**Explanation:** PII requires controlled access and protection.

---

## Q47. A system has weak logging. Consequences include:

- A) Harder detection
- B) Harder investigation
- C) Reduced accountability
- D) Better forensics
- E) Stronger non-repudiation

**Answer:** A, B, C

**Explanation:** Weak logging impairs detection and investigation.

---

## Q48. A company creates an incident response plan. It should define:

- A) Roles and responsibilities
- B) Communication/escalation
- C) Containment/recovery steps
- D) No documentation
- E) Ad hoc decisions only

**Answer:** A, B, C

**Explanation:** IR plans define roles, communication, and response steps.

---

## Q49. A remote worker uses public Wi-Fi without VPN. Risks include:

- A) Eavesdropping
- B) Session hijacking
- C) Credential interception
- D) Guaranteed confidentiality
- E) Stronger integrity

**Answer:** A, B, C

**Explanation:** Unprotected public Wi-Fi exposes traffic to interception.

---

## Q50. A company implements asset management inventory. This helps:

- A) Know what to protect
- B) Patch/vulnerability coverage
- C) Incident response scoping
- D) Hide unknown assets
- E) Eliminate governance

**Answer:** A, B, C

**Explanation:** Asset inventory is foundational for security.

---

## Q51. A security policy is effective when it is:

- A) Communicated
- B) Understandable
- C) Enforced
- D) Secret from everyone
- E) Written but ignored

**Answer:** A, B, C

**Explanation:** Policies must be communicated, understood, and enforced.

---

## Q52. A firm uses immutable backups for ransomware resilience. Benefits include:

- A) Recovery option
- B) Protection from backup tampering
- C) Business continuity support
- D) Replacing all other controls
- E) Preventing all phishing

**Answer:** A, B, C

**Explanation:** Immutable backups support recovery but are not a replacement for all controls.

---

## Q53. A database is publicly exposed but contains no sensitive data. Still, risks include:

- A) Unauthorized modification
- B) Use as attack pivot/resource abuse
- C) Reputation/operational impact
- D) No risk at all
- E) Guaranteed safety

**Answer:** A, B, C

**Explanation:** Even non-sensitive systems can be abused or modified.

---

## Q54. A company uses strong passwords but stores them in plaintext. This is bad because:

- A) Database compromise exposes credentials
- B) Credential reuse increases impact
- C) It violates good security practice
- D) Plaintext storage improves security
- E) Hashing is unnecessary

**Answer:** A, B, C

**Explanation:** Passwords should be securely hashed; plaintext storage is dangerous.

---

## Q55. A secure physical server room should have:

- A) Access controls
- B) Monitoring/surveillance
- C) Environmental protections where appropriate
- D) Unlocked doors for convenience
- E) Public access

**Answer:** A, B, C

**Explanation:** Physical security includes access, monitoring, and environmental controls.

---

## Q56. A company discovers shadow IT cloud services. Risks include:

- A) Lack of visibility/control
- B) Data leakage/compliance issues
- C) Unmanaged security settings
- D) Guaranteed compliance
- E) Automatic governance

**Answer:** A, B, C

**Explanation:** Shadow IT creates unmanaged risk.

---

## Q57. A phishing simulation program can help by:

- A) Measuring awareness
- B) Training users
- C) Identifying risky behaviors
- D) Punishing all users without training
- E) Replacing technical controls

**Answer:** A, B, C

**Explanation:** Simulations should be used for training and measurement.

---

## Q58. A company implements DLP controls. They can help:

- A) Detect/prevent sensitive data exfiltration
- B) Enforce data handling policies
- C) Increase visibility into data flows
- D) Make data public
- E) Remove need for classification

**Answer:** A, B, C

**Explanation:** DLP supports monitoring and policy enforcement for sensitive data.

---

## Q59. A critical patch is delayed due to downtime concerns. Good practice includes:

- A) Risk assessment
- B) Temporary compensating controls
- C) Scheduled patch window
- D) Permanent delay with no review
- E) Ignoring the vulnerability

**Answer:** A, B, C

**Explanation:** Delays should be risk-managed with compensating controls and scheduling.

---

## Q60. A company reviews access rights quarterly. This helps:

- A) Remove unnecessary access
- B) Enforce least privilege
- C) Reduce insider/excess privilege risk
- D) Grant permanent access to all
- E) Avoid accountability

**Answer:** A, B, C

**Explanation:** Access reviews support least privilege.

---

## Q61. An application logs authentication failures and unusual access patterns. This supports:

- A) Detection of brute force/account abuse
- B) Auditability
- C) Incident investigation
- D) Hiding attacks
- E) Disabling monitoring

**Answer:** A, B, C

**Explanation:** Logging supports detection and investigation.

---

## Q62. A company uses secure email gateways and attachment sandboxing. This reduces:

- A) Malicious attachment risk
- B) Phishing/malware delivery
- C) Some email-borne threats
- D) All human error
- E) Need for user awareness completely

**Answer:** A, B, C

**Explanation:** Email security controls reduce but do not eliminate all risk.

---

## Q63. A server is hardened by removing unused services, changing defaults, and applying patches. This reduces:

- A) Attack surface
- B) Known vulnerabilities
- C) Misconfiguration risk
- D) All future vulnerabilities
- E) Need for monitoring

**Answer:** A, B, C

**Explanation:** Hardening reduces attack surface and known risks.

---

## Q64. A company requires MFA for admins. This is especially important because:

- A) Admin accounts have high privilege
- B) Compromise impact is severe
- C) Credentials can be phished/stolen
- D) Admin accounts need no protection
- E) Admins should share accounts

**Answer:** A, B, C

**Explanation:** Privileged accounts require stronger controls.

---

## Q65. A firm performs threat modeling during design. Benefits include:

- A) Early identification of risks
- B) Better control selection
- C) Reduced costly redesign later
- D) Guarantee of no vulnerabilities
- E) No need for testing

**Answer:** A, B, C

**Explanation:** Threat modeling improves early risk management.

---

## Q66. A company has incident communication plan for customers, regulators, and executives. This helps:

- A) Coordinated response
- B) Compliance/expectation management
- C) Reduce confusion
- D) Hide all incidents always
- E) Avoid accountability

**Answer:** A, B, C

**Explanation:** Communication planning supports coordinated response.

---

## Q67. A lost smartphone had company email access. Controls to reduce risk include:

- A) Mobile device management
- B) Remote wipe/lock
- C) MFA and device encryption
- D) No screen lock
- E) Shared device PINs

**Answer:** A, B, C

**Explanation:** MDM, remote wipe, encryption, and MFA reduce mobile risk.

---

## Q68. A security team uses risk register. It should track:

- A) Risk description and owner
- B) Likelihood/impact and treatment
- C) Status and review date
- D) Only resolved risks and nothing else
- E) No ownership

**Answer:** A, B, C

**Explanation:** Risk registers track ownership, assessment, treatment, and status.

---

## Q69. A company isolates infected endpoints during malware outbreak. This supports:

- A) Containment
- B) Limiting spread
- C) Protecting other systems
- D) Faster malware propagation
- E) Evidence destruction

**Answer:** A, B, C

**Explanation:** Isolation contains incidents.

---

## Q70. A secure password policy should consider:

- A) Length/strength
- B) MFA where possible
- C) Protection against brute force
- D) Encouraging password reuse
- E) Plaintext storage

**Answer:** A, B, C

**Explanation:** Modern password controls emphasize strength, MFA, and brute-force protections.

---

## Q71. A firm uses encryption but poor key management. Risks include:

- A) Data unavailable if keys lost
- B) Unauthorized decryption if keys exposed
- C) False sense of security
- D) No key management risk
- E) Automatic compliance

**Answer:** A, B, C

**Explanation:** Key management is critical to encryption effectiveness.

---

## Q72. A company monitors privileged account activity. This helps detect:

- A) Abuse/misuse
- B) Compromised admin credentials
- C) Policy violations
- D) Guaranteed prevention of all attacks
- E) No need for least privilege

**Answer:** A, B, C

**Explanation:** Monitoring helps detect but not guarantee prevention.

---

## Q73. A backup restoration test fails. Appropriate actions include:

- A) Investigate cause
- B) Fix backup/recovery process
- C) Retest until reliable
- D) Assume backups are fine
- E) Delete backup policy

**Answer:** A, B, C

**Explanation:** Failed restore tests require remediation and retesting.

---

## Q74. A company implements secure API authentication and rate limiting. This reduces:

- A) Abuse/unauthorized access
- B) Brute force/automation abuse
- C) Some DoS/resource abuse risks
- D) All vulnerabilities
- E) Need for input validation

**Answer:** A, B, C

**Explanation:** Auth and rate limiting reduce abuse but not all vulnerabilities.

---

## Q75. A security governance program includes policies, roles, metrics, and audits. This provides:

- A) Direction and oversight
- B) Accountability
- C) Continuous evaluation
- D) Guaranteed no incidents
- E) No need for management

**Answer:** A, B, C

**Explanation:** Governance provides oversight and accountability, not guarantees.

---

## Q76. A company discovers employees sharing accounts. Problems include:

- A) Poor accountability
- B) Difficult auditing
- C) Increased misuse risk
- D) Strong non-repudiation
- E) Clear attribution

**Answer:** A, B, C

**Explanation:** Shared accounts undermine accountability and auditing.

---

## Q77. A cloud storage bucket is misconfigured as public. Response should include:

- A) Restrict access immediately
- B) Assess exposed data
- C) Review logs and root cause
- D) Ignore if no one complained
- E) Leave it public

**Answer:** A, B, C

**Explanation:** Misconfiguration requires containment, impact assessment, and investigation.

---

## Q78. A company uses change control and peer review for production changes. This reduces:

- A) Errors/misconfigurations
- B) Unauthorized changes
- C) Operational risk
- D) All downtime
- E) Need for testing

**Answer:** A, B, C

**Explanation:** Change control reduces but cannot eliminate all downtime.

---

## Q79. A security policy requires data classification labels. This helps:

- A) Apply appropriate controls
- B) Inform sharing/handling decisions
- C) Support compliance
- D) Make all data public
- E) Remove access controls

**Answer:** A, B, C

**Explanation:** Labels guide handling and controls.

---

## Q80. An organization adopts zero-trust principles. This may involve:

- A) Verify explicitly
- B) Least privilege
- C) Assume breach/segment
- D) Trust all internal traffic automatically
- E) Remove authentication

**Answer:** A, B, C

**Explanation:** Zero trust emphasizes verification, least privilege, and segmentation.

---

## Q81. A company experiences repeated phishing clicks. Improvements may include:

- A) Targeted training
- B) Better email filtering/reporting tools
- C) MFA and access controls
- D) No action
- E) Removing reporting channels

**Answer:** A, B, C

**Explanation:** Training, technical controls, and access controls help.

---

## Q82. A developer leaves debug endpoint enabled in production. Risks include:

- A) Information disclosure
- B) Unauthorized access/abuse
- C) Increased attack surface
- D) Improved security
- E) Reduced exposure

**Answer:** A, B, C

**Explanation:** Debug endpoints can expose information and functionality.

---

## Q83. A firm stores customer PII longer than needed. Risks include:

- A) Greater breach impact
- B) Compliance/privacy risk
- C) Unnecessary data exposure
- D) Reduced liability automatically
- E) Better minimization

**Answer:** A, B, C

**Explanation:** Unnecessary retention increases risk.

---

## Q84. A company uses centralized logging and time synchronization. This helps:

- A) Correlate events
- B) Investigate incidents
- C) Support audits
- D) Remove need for security tools
- E) Delete evidence faster

**Answer:** A, B, C

**Explanation:** Centralized, time-synced logs aid investigation and audits.

---

## Q85. A ransomware playbook should include:

- A) Isolation/containment steps
- B) Backup recovery process
- C) Communication/escalation
- D) Paying ransom as first mandatory step
- E) Ignoring backups

**Answer:** A, B, C

**Explanation:** Playbooks should cover containment, recovery, and communication.

---

## Q86. A company reviews firewall rules and removes unused ones. This helps:

- A) Reduce attack surface
- B) Improve manageability
- C) Enforce least access
- D) Allow all traffic
- E) Increase exposure

**Answer:** A, B, C

**Explanation:** Rule review reduces unnecessary exposure.

---

## Q87. A system admin uses personal email for password resets. Risks include:

- A) Loss of organizational control
- B) Account recovery abuse
- C) Audit/compliance issues
- D) Better enterprise security
- E) Stronger governance

**Answer:** A, B, C

**Explanation:** Personal accounts reduce control and auditability.

---

## Q88. A company implements secure disposal for old drives. This prevents:

- A) Data remanence/leakage
- B) Unauthorized recovery of data
- C) Privacy/compliance issues
- D) Need for backups
- E) Need for encryption ever

**Answer:** A, B, C

**Explanation:** Secure disposal prevents data recovery.

---

## Q89. A critical vulnerability has public exploit code. Prioritization should consider:

- A) Exploit availability
- B) Asset criticality/exposure
- C) Potential impact
- D) Ignoring it because it's hard
- E) Waiting indefinitely

**Answer:** A, B, C

**Explanation:** Exploitable, exposed, critical vulnerabilities should be prioritized.

---

## Q90. A company uses security champions in dev teams. Benefits include:

- A) Better security awareness in development
- B) Earlier issue identification
- C) Improved collaboration with security team
- D) Eliminating security team
- E) Removing code review

**Answer:** A, B, C

**Explanation:** Security champions support, not replace, security teams.

---

## Q91. A firm enforces MFA, device compliance, and least privilege for remote access. This supports:

- A) Reduced unauthorized access
- B) Defense in depth
- C) Better remote security posture
- D) Unrestricted access
- E) Shared credentials

**Answer:** A, B, C

**Explanation:** Layered remote access controls reduce risk.

---

## Q92. A company notices unusual privileged login at 3 AM. Appropriate steps include:

- A) Investigate alert
- B) Verify legitimacy with user/change records
- C) Contain if suspicious
- D) Ignore outside business hours
- E) Disable logging

**Answer:** A, B, C

**Explanation:** Alerts should be investigated and contained if suspicious.

---

## Q93. A web app stores session tokens insecurely. Risks include:

- A) Session hijacking
- B) Account takeover
- C) Unauthorized actions
- D) Stronger authentication
- E) Better integrity

**Answer:** A, B, C

**Explanation:** Insecure session handling can lead to takeover.

---

## Q94. A company uses data backups and replication across regions. This helps with:

- A) Disaster recovery
- B) Availability/resilience
- C) Business continuity
- D) Confidentiality only
- E) Eliminating all threats

**Answer:** A, B, C

**Explanation:** Replication and backups support DR and availability.

---

## Q95. A vendor requires remote admin access. Security controls should include:

- A) Least privilege and time-limited access
- B) Monitoring/logging
- C) Strong authentication/MFA
- D) Shared unnamed accounts
- E) Unmonitored persistent access

**Answer:** A, B, C

**Explanation:** Third-party access should be controlled and monitored.

---

## Q96. A company documents and tests its IR plan annually. This improves:

- A) Preparedness
- B) Role clarity
- C) Response effectiveness
- D) Guaranteed no incidents
- E) No need for tools

**Answer:** A, B, C

**Explanation:** Testing improves readiness but not guarantees.

---

## Q97. A misconfigured S3 bucket exposed customer files. Root causes to examine include:

- A) Configuration management
- B) Access control policies
- C) Monitoring/review gaps
- D) Only user bad luck
- E) No process issues

**Answer:** A, B, C

**Explanation:** Root cause often includes config, access control, and monitoring gaps.

---

## Q98. A company uses endpoint detection and response (EDR). It can help with:

- A) Detecting suspicious endpoint behavior
- B) Investigation/response
- C) Visibility into endpoint threats
- D) Replacing all security controls
- E) Eliminating need for patching

**Answer:** A, B, C

**Explanation:** EDR supports detection and response but is not sufficient alone.

---

## Q99. A secure development team handles secrets properly by:

- A) Using secret managers/vaults
- B) Rotating credentials
- C) Avoiding hardcoding in code/repos
- D) Publishing secrets in wiki
- E) Emailing secrets in plaintext

**Answer:** A, B, C

**Explanation:** Secrets should be managed, rotated, and not hardcoded.

---

## Q100. A company applies privacy notice, consent where required, and data access controls. This supports:

- A) Privacy compliance
- B) Transparency
- C) Data protection
- D) Unrestricted data use
- E) Hidden collection

**Answer:** A, B, C

**Explanation:** Privacy programs require transparency and controls.

---

## Q101. A critical system has no owner assigned. Risks include:

- A) Unclear accountability
- B) Delayed patching/decisions
- C) Poor governance
- D) Better security
- E) Faster response

**Answer:** A, B, C

**Explanation:** Ownership is needed for accountability and maintenance.

---

## Q102. A company implements network monitoring and IDS alerts. This helps with:

- A) Detecting suspicious traffic
- B) Incident investigation
- C) Situational awareness
- D) Preventing all attacks automatically
- E) Replacing firewalls completely

**Answer:** A, B, C

**Explanation:** Monitoring improves detection and awareness.

---

## Q103. A firm applies strong onboarding/offboarding access processes. This reduces:

- A) Orphaned accounts
- B) Excessive access
- C) Insider/access misuse risk
- D) Need for access reviews
- E) Accountability

**Answer:** A, B, C

**Explanation:** Onboarding/offboarding controls reduce access risk.

---

## Q104. A company uses secure configuration benchmarks. This helps:

- A) Standardize hardening
- B) Reduce misconfigurations
- C) Support audits
- D) Guarantee no vulnerabilities
- E) Remove patching need

**Answer:** A, B, C

**Explanation:** Benchmarks improve consistency and hardening.

---

## Q105. A security team evaluates likelihood and impact before selecting controls. This is:

- A) Risk-based decision making
- B) Governance/management good practice
- C) Prioritization
- D) Random selection
- E) Control avoidance

**Answer:** A, B, C

**Explanation:** Risk-based prioritization supports effective control selection.

---

## Q106. A company responds to a breach by notifying affected parties as required and improving controls. This shows:

- A) Compliance/response
- B) Accountability
- C) Lessons learned/improvement
- D) Ignoring incident
- E) Cover-up

**Answer:** A, B, C

**Explanation:** Response should include compliance, accountability, and improvement.

---

## Q107. A developer uses input validation and output encoding. This helps prevent:

- A) Injection/XSS issues
- B) Malformed input abuse
- C) Some application-layer attacks
- D) All security issues
- E) Physical attacks

**Answer:** A, B, C

**Explanation:** Validation and encoding reduce common app attacks but not all issues.

---

## Q108. A company enforces least privilege on cloud IAM roles. Benefits include:

- A) Reduced blast radius
- B) Limited unauthorized actions
- C) Better control over access
- D) All users become admins
- E) No logging needed

**Answer:** A, B, C

**Explanation:** Least privilege limits access and impact.

---

## Q109. A firm adopts security metrics and reports to leadership. This supports:

- A) Governance oversight
- B) Informed decisions
- C) Accountability
- D) Security by obscurity
- E) Hiding risk

**Answer:** A, B, C

**Explanation:** Metrics support oversight and decision making.

---

## Q110. A company finds critical logs were deleted. This affects:

- A) Investigation capability
- B) Accountability/non-repudiation support
- C) Detection/forensics
- D) Confidence in records
- E) Log integrity positively

**Answer:** A, B, C, D

**Explanation:** Log deletion harms investigation, accountability, and confidence in records.

---

## Q111. A company implements secure remote admin via bastion host, MFA, and logging. This improves:

- A) Access control
- B) Auditability
- C) Reduced exposure
- D) Anonymous admin access
- E) Unmonitored access

**Answer:** A, B, C

**Explanation:** Bastion/MFA/logging improve controlled access.

---

## Q112. A data classification policy requires encryption for restricted data. This links:

- A) Classification to control selection
- B) Policy to technical enforcement
- C) Risk-based protection
- D) Random controls
- E) Unclassified handling

**Answer:** A, B, C

**Explanation:** Classification should drive appropriate controls.

---

## Q113. A company detects brute-force login attempts on VPN. Effective responses include:

- A) Enforce MFA
- B) Rate limit/lockout policies
- C) Monitor and block suspicious IPs
- D) Disable all logging
- E) Remove authentication

**Answer:** A, B, C

**Explanation:** MFA, throttling, and monitoring/blocking reduce brute-force risk.

---

## Q114. An employee emails an unencrypted spreadsheet of customer SSNs. Controls to prevent recurrence include:

- A) DLP/email encryption
- B) User training and policy
- C) Data classification/handling rules
- D) Encourage plaintext sharing
- E) Disable all controls

**Answer:** A, B, C

**Explanation:** Technical and administrative controls reduce sensitive data mishandling.

---

## Q115. A critical web app has no WAF and no input validation. Risks include:

- A) Injection attacks
- B) Application-layer abuse
- C) Data compromise
- D) Complete immunity
- E) Reduced attack surface

**Answer:** A, B, C

**Explanation:** Missing app-layer controls increases exposure.

---

## Q116. A company adopts patch cadence and emergency patch process. This helps:

- A) Reduce exposure window
- B) Handle critical vulnerabilities quickly
- C) Improve vulnerability management
- D) Eliminate all bugs
- E) Remove need for testing

**Answer:** A, B, C

**Explanation:** Patch processes reduce exposure but not all bugs.

---

## Q117. After acquiring a company, no security assessment was done before network integration. Risks include:

- A) Inheriting vulnerabilities
- B) Lateral movement paths
- C) Compliance gaps
- D) Automatic security improvement
- E) Guaranteed isolation

**Answer:** A, B, C

**Explanation:** M&A integration without assessment can import risk.

---

## Q118. A SOC analyst sees alerts but no playbook exists. Consequences include:

- A) Inconsistent response
- B) Slower containment
- C) Missed steps
- D) Guaranteed perfect response
- E) Better evidence handling automatically

**Answer:** A, B, C

**Explanation:** Playbooks improve consistency and speed.

---

## Q119. A company uses shared admin credentials for emergency access. Better alternatives include:

- A) Break-glass accounts with monitoring
- B) Individual accountability/MFA
- C) Vaulted credentials
- D) Anonymous shared password on sticky note
- E) Unlogged shared access

**Answer:** A, B, C

**Explanation:** Controlled emergency access preserves accountability.

---

## Q120. A database backup is stored in same rack as primary server. This is risky because:

- A) Single physical incident can destroy both
- B) Reduces disaster resilience
- C) Violates resilience good practice
- D) Guarantees availability
- E) Improves offsite recovery

**Answer:** A, B, C

**Explanation:** Backups should be separated for resilience.

---

## Q121. A company implements endpoint hardening and application allowlisting. This can reduce:

- A) Unauthorized software execution
- B) Malware impact
- C) Attack surface
- D) Need for all other controls
- E) Need for patching completely

**Answer:** A, B, C

**Explanation:** Hardening and allowlisting reduce attack surface but are not sufficient alone.

---

## Q122. A team discovers API keys exposed in public Git repo. Immediate actions include:

- A) Revoke/rotate keys
- B) Assess abuse/logs
- C) Remove secrets and prevent recurrence
- D) Ignore because repo is old
- E) Publish more keys

**Answer:** A, B, C

**Explanation:** Exposed keys must be rotated and investigated.

---

## Q123. A company deploys CASB for sanctioned cloud apps. This can help:

- A) Visibility into cloud use
- B) Policy enforcement
- C) Data protection controls
- D) Eliminate all cloud risk
- E) Replace identity management

**Answer:** A, B, C

**Explanation:** CASB provides visibility and control but not total risk elimination.

---

## Q124. A security team uses tabletop exercises. Benefits include:

- A) Testing IR plan
- B) Identifying gaps
- C) Improving coordination
- D) Replacing real controls
- E) Eliminating incidents

**Answer:** A, B, C

**Explanation:** Tabletops improve preparedness and coordination.

---

## Q125. A firm encrypts laptops but does not manage recovery keys. Risks include:

- A) Data loss if keys unavailable
- B) Operational disruption
- C) Poor key management
- D) No impact
- E) Stronger availability automatically

**Answer:** A, B, C

**Explanation:** Key management is essential for usable encryption.

---

## Q126. The CIA triad stands for:

- A) Confidentiality, Integrity, Availability
- B) Control, Integrity, Authentication
- C) Confidentiality, Identity, Authorization
- D) Compliance, Integrity, Availability
- E) Cryptography, Identity, Accounting

**Answer:** A

**Explanation:** CIA is Confidentiality, Integrity, Availability.

---

## Q127. Non-repudiation means:

- A) Inability to credibly deny an action
- B) Encrypting data
- C) Backing up files
- D) Blocking ports
- E) Scanning vulnerabilities

**Answer:** A

**Explanation:** Non-repudiation prevents denial of actions.

---

## Q128. A vulnerability is:

- A) A weakness that can be exploited
- B) An attack in progress
- C) A security control
- D) A backup
- E) A business objective

**Answer:** A

**Explanation:** A vulnerability is a weakness.

---

## Q129. A threat is:

- A) A potential cause of an unwanted incident
- B) A patch
- C) A firewall rule
- D) An audit log
- E) A control baseline

**Answer:** A

**Explanation:** A threat is a potential cause of harm.

---

## Q130. Risk is commonly assessed by:

- A) Likelihood and impact
- B) Only impact
- C) Only likelihood
- D) Only vulnerability count
- E) Only asset value

**Answer:** A

**Explanation:** Risk considers likelihood and impact.

---

## Q131. Defense in depth means:

- A) Multiple layers of security controls
- B) One strong control
- C) No controls
- D) Only physical security
- E) Only encryption

**Answer:** A

**Explanation:** Defense in depth uses layered controls.

---

## Q132. Least privilege means:

- A) Granting only access needed for duties
- B) Giving all users admin
- C) Removing all access
- D) Sharing passwords
- E) Permanent access

**Answer:** A

**Explanation:** Least privilege limits access rights.

---

## Q133. MFA stands for:

- A) Multi-Factor Authentication
- B) Multiple File Access
- C) Managed Firewall Application
- D) Main Frame Authorization
- E) Multi-Form Audit

**Answer:** A

**Explanation:** MFA uses multiple authentication factors.

---

## Q134. An incident response plan defines:

- A) How to detect, respond, and recover from incidents
- B) Only backups
- C) Only passwords
- D) Only procurement
- E) Only development

**Answer:** A

**Explanation:** IR plans guide response and recovery.

---

## Q135. A control is:

- A) A safeguard/countermeasure to reduce risk
- B) A vulnerability
- C) An exploit
- D) A threat actor
- E) An incident

**Answer:** A

**Explanation:** Controls reduce risk.

---

## Q136. Authentication is:

- A) Verifying identity
- B) Granting permissions
- C) Encrypting data
- D) Logging events
- E) Backing up data

**Answer:** A

**Explanation:** Authentication verifies identity.

---

## Q137. Authorization is:

- A) Granting permissions to an authenticated entity
- B) Verifying identity
- C) Creating backups
- D) Encrypting disks
- E) Writing policies

**Answer:** A

**Explanation:** Authorization determines allowed actions.

---

## Q138. Accounting in AAA refers to:

- A) Tracking/logging actions
- B) Financial accounting
- C) Encryption
- D) Patch management
- E) User provisioning only

**Answer:** A

**Explanation:** AAA accounting tracks actions.

---

## Q139. Encryption at rest protects:

- A) Data stored on media
- B) Data in transit only
- C) CPU speed
- D) Network cables
- E) Usernames only

**Answer:** A

**Explanation:** At-rest encryption protects stored data.

---

## Q140. Encryption in transit protects:

- A) Data moving over networks
- B) Data on disk only
- C) Backups only
- D) Password policies
- E) Physical doors

**Answer:** A

**Explanation:** In-transit encryption protects network data.

---

## Q141. A security baseline is:

- A) A minimum security configuration standard
- B) Maximum risk
- C) An incident
- D) A virus
- E) A patch

**Answer:** A

**Explanation:** A baseline defines minimum secure configuration.

---

## Q142. Segregation of duties helps prevent:

- A) One person having excessive control
- B) Encryption
- C) Backups
- D) Patching
- E) Logging

**Answer:** A

**Explanation:** SoD reduces fraud and error.

---

## Q143. Phishing is:

- A) Social engineering to trick users into revealing info or taking action
- B) A firewall
- C) Disk encryption
- D) Backup
- E) Patch management

**Answer:** A

**Explanation:** Phishing uses deception.

---

## Q144. Ransomware typically:

- A) Encrypts/locks data for extortion
- B) Improves backups
- C) Patches systems
- D) Creates certificates
- E) Monitors uptime

**Answer:** A

**Explanation:** Ransomware denies access for ransom.

---

## Q145. A SIEM is used for:

- A) Centralized log collection, correlation, and alerting
- B) Writing code
- C) Physical access
- D) Disk formatting
- E) Backup storage only

**Answer:** A

**Explanation:** SIEM aggregates and correlates security events.

---

## Q146. A backup is:

- A) A copy of data for recovery
- B) A threat
- C) An exploit
- D) A firewall
- E) A vulnerability

**Answer:** A

**Explanation:** Backups support recovery.

---

## Q147. Vulnerability management includes:

- A) Identifying, prioritizing, and remediating vulnerabilities
- B) Ignoring scans
- C) Only buying tools
- D) Deleting logs
- E) Only patching annually

**Answer:** A

**Explanation:** Vulnerability management is a continuous process.

---

## Q148. Patch management is:

- A) Process for deploying updates/fixes
- B) Creating vulnerabilities
- C) Removing backups
- D) Disabling logging
- E) Sharing passwords

**Answer:** A

**Explanation:** Patch management deploys fixes.

---

## Q149. Data classification helps:

- A) Determine appropriate protection levels
- B) Make all data public
- C) Remove security
- D) Disable access controls
- E) Avoid compliance

**Answer:** A

**Explanation:** Classification guides protection.

---

## Q150. Business continuity focuses on:

- A) Maintaining operations during/after disruption
- B) Only encryption
- C) Only firewalls
- D) Only audits
- E) Only development

**Answer:** A

**Explanation:** Business continuity maintains critical operations.

---

