---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1032"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1032: Multi-factor Authentication — Defensive Application

## Source record

- [[01 ATT&CK/M1032 - Multi-factor Authentication|M1032 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Multi-Factor Authentication (MFA) enhances security by requiring users to provide at least two forms of verification to prove their identity before granting access. These factors typically include: - *Something you know*: Passwords, PINs. - *Something you have*: Physical tokens, smartphone authenticator apps. - *Something you are*: Biometric data such as fingerprints, facial recognition, or retinal scans. Implementing MFA across all critical systems and services ensures robust protection against account takeover and unauthorized access. This mitigation can be implemented through the following measures: Identity and Access Management (IAM): - Use IAM solutions like Azure Active Directory, Okta, or AWS IAM to enforce MFA policies for all user logins, especially for privileged roles. - Enable conditional access policies to enforce MFA for risky sign-ins (e.g., unfamiliar devices, geolocations). - Enable Conditional Access policies to only allow logins from trusted devices, such as those enrolled in Intune or joined via Hybrid/Entra. Authentication Tools and Methods: - Use authenticator applications such as Google Authenticator, Microsoft Authenticator, or Authy for time-based one-time passwords (TOTP). - Deploy hardware-based tokens like YubiKey, RSA SecurID, or smart cards for additional security. - Enforce biometric authentication for compatible devices and applications. Secure Legacy Systems: - Integrate MFA solutions with older systems using third-party tools like Duo Security or Thales SafeNet. - Enable RADIUS/NPS servers to facilitate MFA for VPNs, RDP, and other network logins. Monitoring and Alerting: - Use SIEM tools to monitor failed MFA attempts, login anomalies, or brute-force attempts against MFA systems. - Implement alerts for suspicious MFA activities, such as repeated failed codes or new device registrations. Training and Policy Enforcement: - Educate employees on the importance of MFA and secure authenticator usage. - Enforce policies that require MFA on all critical systems, especially for remote access, privileged accounts, and cloud applications.

## Defensive focus

Assess the control as an implementable safeguard with a defined owner, target population, configuration, exception path, and evidence of operation.

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Review checklist

- Which assets and versions support this control, and where are exceptions required?
- Does the control reduce the relevant exposure without disabling a legitimate business function?
- How is coverage measured and configuration drift detected?
- What compensating control applies where the primary safeguard is unavailable?
- What test demonstrates continued effectiveness after updates?

## Safe validation

Pilot configuration changes in a representative test group, obtain owner approval, and preserve a tested rollback plan. Define written scope, test window, accounts, data boundaries, and stop conditions in advance. Preserve only the evidence required to verify the control and protect it from unauthorized access.

## Evidence and response

Record the source and version, environment, time range, expected behavior, observations, alternative explanations, and telemetry gaps. A catalog mapping is a lead for analysis, not an incident finding. Escalate and contain only under approved response procedures; verify remediation with a measurable retest.

## Further reading

- [MITRE ATT&CK](https://attack.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
