---
type: "Technique"
source: MITRE ATT&CK
id: "T1201"
source_url: "https://attack.mitre.org/techniques/T1201"
created: "2018-04-18"
modified: "2025-10-24"
---
# T1201: Password Policy Discovery

> **Defensive knowledge record.** Use this entry to support detection, prevention, incident response, and security education. Descriptions summarize the source; validate decisions against current systems and threat context.

**Class:** Technique  
**ATT&CK ID:** T1201  
**Platforms:** Windows, Linux, macOS, IaaS, Network Devices, Identity Provider, SaaS, Office Suite  
**Tactics:** discovery

## Source description

Adversaries may attempt to access detailed information about the password policy used within an enterprise network or cloud environment. Password policies are a way to enforce complex passwords that are difficult to guess or crack through [Brute Force](https://attack.mitre.org/techniques/T1110). This information may help the adversary to create a list of common passwords and launch dictionary and/or brute force attacks which adheres to the policy (e.g. if the minimum password length should be 8, then not trying passwords such as 'pass123'; not checking for more than 3-4 passwords per account if the lockout is set to 6 as to not lock out accounts). Password policies can be set and discovered on Windows, Linux, and macOS systems via various command shell utilities such as net accounts (/domain) , Get-ADDefaultDomainPasswordPolicy , chage -l , cat /etc/pam.d/common-password , and pwpolicy getaccountpolicies (Citation: Superuser Linux Password Policies) (Citation: Jamf User Password Policies). Adversaries may also leverage a [Network Device CLI](https://attack.mitre.org/techniques/T1059/008) on network devices to discover password policy information (e.g. show aaa , show aaa common-criteria policy all ).(Citation: US-CERT-TA18-106A) Password policies can be discovered in cloud environments using available APIs such as GetAccountPasswordPolicy in AWS (Citation: AWS GetPasswordPolicy).

## Defensive use

Use this record as a prompt for threat modeling and defensive review. Identify relevant assets and trust boundaries, determine whether the behavior is applicable to the environment, then consult detection and mitigation references before acting. A technique or tool listing alone is not evidence that an incident occurred.

## Source

- [MITRE ATT&CK: T1201](https://attack.mitre.org/techniques/T1201)
- Dataset: [MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot retrieved 2026-09-30.
