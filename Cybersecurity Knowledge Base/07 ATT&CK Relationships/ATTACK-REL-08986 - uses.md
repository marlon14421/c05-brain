---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0082"
target_object: "T1218.001"
stix_relationship_id: "relationship--cbd7249a-918d-436b-805a-0199eed6567a"
---
# Relationship 8986: G0082 — uses → T1218.001

**Source object:** [[01 ATT&CK/G0082 - APT38|G0082: APT38]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.001 - Compiled HTML File|T1218.001: Compiled HTML File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT38](https://attack.mitre.org/groups/G0082) has used CHM files to move concealed payloads.(Citation: Kaspersky Lazarus Under The Hood APR 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cbd7249a-918d-436b-805a-0199eed6567a`.
