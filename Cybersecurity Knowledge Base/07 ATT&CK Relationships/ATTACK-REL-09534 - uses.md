---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0023"
target_object: "S0029"
stix_relationship_id: "relationship--ead3f010-b221-4708-bb1e-d146f2593be5"
---
# Relationship 9534: C0023 — uses → S0029

**Source object:** [[01 ATT&CK/C0023 - Operation Ghost|C0023: Operation Ghost]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0029 - PsExec|S0029: PsExec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [Operation Ghost](https://attack.mitre.org/campaigns/C0023), [APT29](https://attack.mitre.org/groups/G0016) used [PsExec](https://attack.mitre.org/software/S0029) for lateral movement on compromised networks.(Citation: ESET Dukes October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ead3f010-b221-4708-bb1e-d146f2593be5`.
