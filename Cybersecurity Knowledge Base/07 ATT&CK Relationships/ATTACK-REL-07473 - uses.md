---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0343"
target_object: "T1112"
stix_relationship_id: "relationship--ab11615f-a0d9-43c9-b71e-6ae83155bf3b"
---
# Relationship 7473: S0343 — uses → T1112

**Source object:** [[01 ATT&CK/S0343 - Exaramel for Windows|S0343: Exaramel for Windows]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Exaramel for Windows](https://attack.mitre.org/software/S0343) adds the configuration to the Registry in XML format.(Citation: ESET TeleBots Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ab11615f-a0d9-43c9-b71e-6ae83155bf3b`.
