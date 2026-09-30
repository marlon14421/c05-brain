---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1059"
target_object: "T1095"
stix_relationship_id: "relationship--45ef2a23-61b6-4f78-9d86-58a2d50a4ee0"
---
# Relationship 8237: S1059 — uses → T1095

**Source object:** [[01 ATT&CK/S1059 - metaMain|S1059: metaMain]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[metaMain](https://attack.mitre.org/software/S1059) can establish an indirect and raw TCP socket-based connection to the C2 server.(Citation: SentinelLabs Metador Sept 2022)(Citation: SentinelLabs Metador Technical Appendix Sept 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45ef2a23-61b6-4f78-9d86-58a2d50a4ee0`.
