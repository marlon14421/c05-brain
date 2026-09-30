---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0579"
target_object: "T1055"
stix_relationship_id: "relationship--56e0b679-1c1b-4c82-9346-bde619c21117"
---
# Relationship 5059: S0579 — uses → T1055

**Source object:** [[01 ATT&CK/S0579 - Waterbear|S0579: Waterbear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Waterbear](https://attack.mitre.org/software/S0579) can inject decrypted shellcode into the LanmanServer service.(Citation: Trend Micro Waterbear December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--56e0b679-1c1b-4c82-9346-bde619c21117`.
