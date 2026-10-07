---
tags:
  - cybersecurity
  - defensive-security
  - attack-review
attack_id: "M1045"
attack_type: "Mitigation"
source: MITRE ATT&CK
---
# M1045: Code Signing — Defensive Application

## Source record

- [[01 ATT&CK/M1045 - Code Signing|M1045 source record]]
- ATT&CK class: Mitigation
- Platforms: Not specified
- Tactics: Not specified

## Source context

Code Signing is a security process that ensures the authenticity and integrity of software by digitally signing executables, scripts, and other code artifacts. It prevents untrusted or malicious code from executing by verifying the digital signatures against trusted sources. Code signing protects against tampering, impersonation, and distribution of unauthorized or malicious software, forming a critical defense against supply chain and software exploitation attacks. This mitigation can be implemented through the following measures: Enforce Signed Code Execution: - Implementation: Configure operating systems (e.g., Windows with AppLocker or Linux with Secure Boot) to allow only signed code to execute. - Use Case: Prevent the execution of malicious PowerShell scripts by requiring all scripts to be signed with a trusted certificate. Vendor-Signed Driver Enforcement: - Implementation: Enable kernel-mode code signing to ensure that only drivers signed by trusted vendors can be loaded. - Use Case: A malicious driver attempting to modify system memory fails to load because it lacks a valid signature. Certificate Revocation Management: - Implementation: Use Online Certificate Status Protocol (OCSP) or Certificate Revocation Lists (CRLs) to block certificates associated with compromised or deprecated code. - Use Case: A compromised certificate used to sign a malicious update is revoked, preventing further execution of the software. Third-Party Software Verification: - Implementation: Require software from external vendors to be signed with valid certificates before deployment. - Use Case: An organization only deploys signed and verified third-party software to prevent supply chain attacks. Script Integrity in CI/CD Pipelines: - Implementation: Integrate code signing into CI/CD pipelines to sign and verify code artifacts before production release. - Use Case: A software company ensures that all production builds are signed, preventing tampered builds from reaching customers. **Key Components of Code Signing** - Digital Signature Verification: Verifies the authenticity of code by ensuring it was signed by a trusted entity. - Certificate Management: Uses Public Key Infrastructure (PKI) to manage signing certificates and revocation lists. - Enforced Policy for Unsigned Code: Prevents the execution of unsigned or untrusted binaries and scripts. - Hash Integrity Check: Confirms that code has not been altered since signing by comparing cryptographic hashes.

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
