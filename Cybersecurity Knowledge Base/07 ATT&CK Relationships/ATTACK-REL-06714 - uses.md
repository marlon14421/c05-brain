---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0137"
target_object: "T1082"
stix_relationship_id: "relationship--5301c007-7c00-4b4d-b355-864db8de052f"
---
# Relationship 6714: S0137 — uses → T1082

**Source object:** [[01 ATT&CK/S0137 - CORESHELL|S0137: CORESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CORESHELL](https://attack.mitre.org/software/S0137) collects hostname and OS version data from the victim and sends the information to its C2 server.(Citation: FireEye APT28)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5301c007-7c00-4b4d-b355-864db8de052f`.
