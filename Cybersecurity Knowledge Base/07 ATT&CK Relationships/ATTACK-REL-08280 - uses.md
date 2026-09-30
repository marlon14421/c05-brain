---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0582"
target_object: "T1140"
stix_relationship_id: "relationship--fdb22ee1-d90b-496b-a7f7-baf155a1930c"
---
# Relationship 8280: S0582 — uses → T1140

**Source object:** [[01 ATT&CK/S0582 - LookBack|S0582: LookBack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LookBack](https://attack.mitre.org/software/S0582) has a function that decrypts malicious data.(Citation: Proofpoint LookBack Malware Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fdb22ee1-d90b-496b-a7f7-baf155a1930c`.
