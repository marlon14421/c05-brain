---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1020"
target_object: "T1608.001"
stix_relationship_id: "relationship--27d95bad-b939-43eb-a683-c3c3367cf728"
---
# Relationship 5386: G1020 — uses → T1608.001

**Source object:** [[01 ATT&CK/G1020 - Mustard Tempest|G1020: Mustard Tempest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.001 - Upload Malware|T1608.001: Upload Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustard Tempest](https://attack.mitre.org/groups/G1020) has hosted payloads on acquired second-stage servers for periods of either days, weeks, or months.(Citation: SentinelOne SocGholish Infrastructure November 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--27d95bad-b939-43eb-a683-c3c3367cf728`.
