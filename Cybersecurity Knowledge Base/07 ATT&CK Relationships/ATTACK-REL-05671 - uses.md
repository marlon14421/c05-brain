---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1047"
target_object: "T1140"
stix_relationship_id: "relationship--7d37a0f1-1aea-456c-ade6-6d463a14fc14"
---
# Relationship 5671: S1047 — uses → T1140

**Source object:** [[01 ATT&CK/S1047 - Mori|S1047: Mori]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mori](https://attack.mitre.org/software/S1047) can resolve networking APIs from strings that are ADD-encrypted.(Citation: DHS CISA AA22-055A MuddyWater February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7d37a0f1-1aea-456c-ade6-6d463a14fc14`.
