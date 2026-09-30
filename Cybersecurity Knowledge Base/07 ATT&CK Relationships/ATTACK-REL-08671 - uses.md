---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0681"
target_object: "T1016"
stix_relationship_id: "relationship--dd18682c-873d-4b26-b41a-2696101f8eb8"
---
# Relationship 8671: S0681 — uses → T1016

**Source object:** [[01 ATT&CK/S0681 - Lizar|S0681: Lizar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lizar](https://attack.mitre.org/software/S0681) has retrieved network information from a compromised host, such as the MAC address.(Citation: BiZone Lizar May 2021)(Citation: SekoiaBourhis_DiceLoader_Feb2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd18682c-873d-4b26-b41a-2696101f8eb8`.
