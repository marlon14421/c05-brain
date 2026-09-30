---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1236"
target_object: "T1140"
stix_relationship_id: "relationship--e9a7ebd2-e8ec-4047-84d2-831018de10ab"
---
# Relationship 7976: S1236 — uses → T1140

**Source object:** [[01 ATT&CK/S1236 - CLAIMLOADER|S1236: CLAIMLOADER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CLAIMLOADER](https://attack.mitre.org/software/S1236) has decoded its payload prior to execution.(Citation: IBM MUSTANG PANDA PUBLOAD CLAIMLOADER JUNE 2025)(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9a7ebd2-e8ec-4047-84d2-831018de10ab`.
