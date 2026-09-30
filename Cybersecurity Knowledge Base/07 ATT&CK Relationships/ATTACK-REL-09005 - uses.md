---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0050"
target_object: "T1036.005"
stix_relationship_id: "relationship--6c216abc-f0ae-4ce1-aa74-6ccf2d42e6a5"
---
# Relationship 9005: C0050 — uses → T1036.005

**Source object:** [[01 ATT&CK/C0050 - J-magic Campaign|C0050: J-magic Campaign]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [J-magic Campaign](https://attack.mitre.org/campaigns/C0050), threat actors used the name “JunoscriptService” to masquerade malware as the Junos automation scripting service.(Citation: Lumen J-Magic JAN 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c216abc-f0ae-4ce1-aa74-6ccf2d42e6a5`.
