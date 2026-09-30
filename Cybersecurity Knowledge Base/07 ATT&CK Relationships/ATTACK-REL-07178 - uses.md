---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0115"
target_object: "T1012"
stix_relationship_id: "relationship--e1caf917-c15f-4388-8ca0-6cdefd01da8f"
---
# Relationship 7178: S0115 — uses → T1012

**Source object:** [[01 ATT&CK/S0115 - Crimson|S0115: Crimson]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Crimson](https://attack.mitre.org/software/S0115) can check the Registry for the presence of HKCU\SOFTWARE\Microsoft\Windows\CurrentVersion\last_edate to determine how long it has been installed on a host.(Citation: Proofpoint Operation Transparent Tribe March 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e1caf917-c15f-4388-8ca0-6cdefd01da8f`.
