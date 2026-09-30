---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0340"
target_object: "T1567.002"
stix_relationship_id: "relationship--6e137013-3837-4b56-8424-4ea6d87044b5"
---
# Relationship 7510: S0340 — uses → T1567.002

**Source object:** [[01 ATT&CK/S0340 - Octopus|S0340: Octopus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Octopus](https://attack.mitre.org/software/S0340) has exfiltrated data to file sharing sites.(Citation: ESET Nomadic Octopus 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e137013-3837-4b56-8424-4ea6d87044b5`.
