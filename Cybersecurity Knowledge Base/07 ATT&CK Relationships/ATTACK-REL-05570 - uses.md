---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0412"
target_object: "T1046"
stix_relationship_id: "relationship--704355c5-4743-4fe1-bd64-b7012fe7c1d2"
---
# Relationship 5570: S0412 — uses → T1046

**Source object:** [[01 ATT&CK/S0412 - ZxShell|S0412: ZxShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZxShell](https://attack.mitre.org/software/S0412) can launch port scans.(Citation: FireEye APT41 Aug 2019)(Citation: Talos ZxShell Oct 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--704355c5-4743-4fe1-bd64-b7012fe7c1d2`.
