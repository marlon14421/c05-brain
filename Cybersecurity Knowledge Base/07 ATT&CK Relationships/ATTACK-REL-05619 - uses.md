---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9028"
target_object: "T1140"
stix_relationship_id: "relationship--0133e2fc-5673-40a5-982b-9b0f441217f5"
---
# Relationship 5619: S9028 — uses → T1140

**Source object:** [[01 ATT&CK/S9028 - PHPsert|S9028: PHPsert]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PHPsert](https://attack.mitre.org/software/S9028) has the ability to decode and decrypt obfuscated strings prior to execution.(Citation: sentinelone operationDigitalEye Dec 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0133e2fc-5673-40a5-982b-9b0f441217f5`.
