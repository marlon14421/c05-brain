---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1237"
target_object: "T1027.007"
stix_relationship_id: "relationship--5e547718-dd81-474a-9d22-af55fe3a3dcc"
---
# Relationship 8635: S1237 — uses → T1027.007

**Source object:** [[01 ATT&CK/S1237 - CANONSTAGER|S1237: CANONSTAGER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.007 - Dynamic API Resolution|T1027.007: Dynamic API Resolution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CANONSTAGER](https://attack.mitre.org/software/S1237) has utilized custom API hashing to obfuscate the Windows APIs being used.(Citation: Google Threat Intelligence Group MUSTANG PANDA PLUGX August 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5e547718-dd81-474a-9d22-af55fe3a3dcc`.
