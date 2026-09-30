---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0279"
target_object: "T1560"
stix_relationship_id: "relationship--e898c937-29b0-4e30-aeed-017ac3bbc3ed"
---
# Relationship 9681: S0279 — uses → T1560

**Source object:** [[01 ATT&CK/S0279 - Proton|S0279: Proton]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560 - Archive Collected Data|T1560: Archive Collected Data]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Proton](https://attack.mitre.org/software/S0279) zips up files before exfiltrating them.(Citation: objsee mac malware 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e898c937-29b0-4e30-aeed-017ac3bbc3ed`.
