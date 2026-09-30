---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0242"
target_object: "T1082"
stix_relationship_id: "relationship--3e58118d-64b9-43ae-bfd8-cb3c8bf19556"
---
# Relationship 9963: S0242 — uses → T1082

**Source object:** [[01 ATT&CK/S0242 - SynAck|S0242: SynAck]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SynAck](https://attack.mitre.org/software/S0242) gathers computer names, OS version info, and also checks installed keyboard layouts to estimate if it has been launched from a certain list of countries.(Citation: SecureList SynAck Doppelgänging May 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e58118d-64b9-43ae-bfd8-cb3c8bf19556`.
