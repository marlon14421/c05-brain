---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1181"
target_object: "T1490"
stix_relationship_id: "relationship--56aabb26-2bc3-428e-b8ea-ed69a2ea80e7"
---
# Relationship 8673: S1181 — uses → T1490

**Source object:** [[01 ATT&CK/S1181 - BlackByte 2.0 Ransomware|S1181: BlackByte 2.0 Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackByte 2.0 Ransomware](https://attack.mitre.org/software/S1181) modifies volume shadow copies during execution in a way that destroys them on the victim machine.(Citation: Microsoft BlackByte 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--56aabb26-2bc3-428e-b8ea-ed69a2ea80e7`.
