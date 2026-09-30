---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0188"
target_object: "T1036.005"
stix_relationship_id: "relationship--90e64a7a-42e6-4b95-ae85-5ac324d7f6e2"
---
# Relationship 5548: S0188 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0188 - Starloader|S0188: Starloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Starloader](https://attack.mitre.org/software/S0188) has masqueraded as legitimate software update packages such as Adobe Acrobat Reader and Intel.(Citation: Symantec Sowbug Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--90e64a7a-42e6-4b95-ae85-5ac324d7f6e2`.
