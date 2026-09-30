---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0012"
target_object: "T1140"
stix_relationship_id: "relationship--4b3f0b38-d4e2-49e8-a8f9-6a186c31967f"
---
# Relationship 5084: G0012 — uses → T1140

**Source object:** [[01 ATT&CK/G0012 - Darkhotel|G0012: Darkhotel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Darkhotel](https://attack.mitre.org/groups/G0012) has decrypted strings and imports using RC4 during execution.(Citation: Securelist Darkhotel Aug 2015)(Citation: Microsoft DUBNIUM July 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4b3f0b38-d4e2-49e8-a8f9-6a186c31967f`.
