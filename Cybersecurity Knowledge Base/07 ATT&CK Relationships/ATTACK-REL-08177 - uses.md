---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0023"
target_object: "T1078.002"
stix_relationship_id: "relationship--0a154ef3-859f-4f13-b5c9-9bd0e91864f0"
---
# Relationship 8177: C0023 — uses → T1078.002

**Source object:** [[01 ATT&CK/C0023 - Operation Ghost|C0023: Operation Ghost]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.002 - Domain Accounts|T1078.002: Domain Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [Operation Ghost](https://attack.mitre.org/campaigns/C0023), [APT29](https://attack.mitre.org/groups/G0016) used stolen administrator credentials for lateral movement on compromised networks.(Citation: ESET Dukes October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0a154ef3-859f-4f13-b5c9-9bd0e91864f0`.
