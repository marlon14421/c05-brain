---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0055"
target_object: "T1095"
stix_relationship_id: "relationship--345c6135-7557-4292-8214-66618ba17edd"
---
# Relationship 8783: S0055 — uses → T1095

**Source object:** [[01 ATT&CK/S0055 - RARSTONE|S0055: RARSTONE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RARSTONE](https://attack.mitre.org/software/S0055) uses SSL to encrypt its communication with its C2 server.(Citation: Aquino RARSTONE)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--345c6135-7557-4292-8214-66618ba17edd`.
