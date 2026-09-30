---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1060"
target_object: "T1114.002"
stix_relationship_id: "relationship--7877810d-3995-43ba-aa44-a9d4f9f85a57"
---
# Relationship 0524: M1060 — mitigates → T1114.002

**Source object:** [[01 ATT&CK/M1060 - Out-of-Band Communications Channel|M1060: Out-of-Band Communications Channel]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1114.002 - Remote Email Collection|T1114.002: Remote Email Collection]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use secure out-of-band authentication methods to verify the authenticity of critical actions initiated via email, such as password resets, financial transactions, or access requests. For highly sensitive information, utilize out-of-band communication channels instead of relying solely on email. This reduces the risk of sensitive data being collected through compromised email accounts. Set up out-of-band alerts to notify security teams of unusual email activities, such as mass forwarding or large attachments being sent, which could indicate email collection attempts. Create plans for leveraging a secure out-of-band communications channel, rather than an existing in-network email server, in case of a security incident.(Citation: TrustedSec OOB Communications)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7877810d-3995-43ba-aa44-a9d4f9f85a57`.
