---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9031"
target_object: "T1036.005"
stix_relationship_id: "relationship--e92df95b-ac85-4926-9b6a-957b342d47ec"
---
# Relationship 5882: S9031 — uses → T1036.005

**Source object:** [[01 ATT&CK/S9031 - AshTag|S9031: AshTag]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AshTag](https://attack.mitre.org/software/S9031) has masqueraded as a legitimate VisualServer utility.(Citation: Palo Alto Ashen Lepus DEC 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e92df95b-ac85-4926-9b6a-957b342d47ec`.
