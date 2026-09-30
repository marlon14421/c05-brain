---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1060"
target_object: "T1114.001"
stix_relationship_id: "relationship--21ad0084-2f19-4559-9de1-dc06d1809ef0"
---
# Relationship 0379: M1060 — mitigates → T1114.001

**Source object:** [[01 ATT&CK/M1060 - Out-of-Band Communications Channel|M1060: Out-of-Band Communications Channel]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1114.001 - Local Email Collection|T1114.001: Local Email Collection]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Implement secure out-of-band alerts to notify security teams of unusual local email activities, such as mass forwarding or large attachments being sent, indicating potential data exfiltration attempts.(Citation: TrustedSec OOB Communications)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--21ad0084-2f19-4559-9de1-dc06d1809ef0`.
