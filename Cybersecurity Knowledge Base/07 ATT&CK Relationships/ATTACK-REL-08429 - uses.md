---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0119"
target_object: "T1558.003"
stix_relationship_id: "relationship--e9ebd661-1095-4638-8231-1ebccf520069"
---
# Relationship 8429: G0119 — uses → T1558.003

**Source object:** [[01 ATT&CK/G0119 - Indrik Spider|G0119: Indrik Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1558.003 - Kerberoasting|T1558.003: Kerberoasting]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Indrik Spider](https://attack.mitre.org/groups/G0119) has conducted Kerberoasting attacks using a module from GitHub.(Citation: Mandiant_UNC2165)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9ebd661-1095-4638-8231-1ebccf520069`.
