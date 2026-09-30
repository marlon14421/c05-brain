---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0547"
target_object: "T1567"
stix_relationship_id: "relationship--6e6910db-1606-43a2-9812-22b5597d8472"
---
# Relationship 9823: S0547 — uses → T1567

**Source object:** [[01 ATT&CK/S0547 - DropBook|S0547: DropBook]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567 - Exfiltration Over Web Service|T1567: Exfiltration Over Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DropBook](https://attack.mitre.org/software/S0547) has used legitimate web services to exfiltrate data.(Citation: BleepingComputer Molerats Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e6910db-1606-43a2-9812-22b5597d8472`.
