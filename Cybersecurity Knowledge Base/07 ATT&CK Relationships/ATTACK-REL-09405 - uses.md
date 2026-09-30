---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0030"
target_object: "T1030"
stix_relationship_id: "relationship--f4182c2a-c2b3-4866-9f7e-f29e0229dead"
---
# Relationship 9405: S0030 — uses → T1030

**Source object:** [[01 ATT&CK/S0030 - Carbanak|S0030: Carbanak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1030 - Data Transfer Size Limits|T1030: Data Transfer Size Limits]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carbanak](https://attack.mitre.org/software/S0030) exfiltrates data in compressed chunks if a message is larger than 4096 bytes .(Citation: FireEye CARBANAK June 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f4182c2a-c2b3-4866-9f7e-f29e0229dead`.
