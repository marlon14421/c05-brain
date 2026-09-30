---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0570"
target_object: "T1135"
stix_relationship_id: "relationship--6743c3f6-7f4f-40b3-bc9e-fe488f81f5e1"
---
# Relationship 9309: S0570 — uses → T1135

**Source object:** [[01 ATT&CK/S0570 - BitPaymer|S0570: BitPaymer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BitPaymer](https://attack.mitre.org/software/S0570) can search for network shares on the domain or workgroup using net view .(Citation: Crowdstrike Indrik November 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6743c3f6-7f4f-40b3-bc9e-fe488f81f5e1`.
