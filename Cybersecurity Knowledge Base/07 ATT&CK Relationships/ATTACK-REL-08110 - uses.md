---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0345"
target_object: "T1027.013"
stix_relationship_id: "relationship--82168e77-bbd9-4da4-b163-7f813df06426"
---
# Relationship 8110: S0345 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0345 - Seasalt|S0345: Seasalt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Seasalt](https://attack.mitre.org/software/S0345) obfuscates configuration data.(Citation: Mandiant APT1 Appendix)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--82168e77-bbd9-4da4-b163-7f813df06426`.
