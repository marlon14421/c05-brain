---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9010"
target_object: "T1059.002"
stix_relationship_id: "relationship--9f2a884d-0974-4080-80a1-13a29a7f25c7"
---
# Relationship 8748: S9010 — uses → T1059.002

**Source object:** [[01 ATT&CK/S9010 - GlassWorm|S9010: GlassWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.002 - AppleScript|T1059.002: AppleScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) has utilized AppleScript to include `set keychainPassword to do shell script` to execute shell command that retrieves passwords from the macOS keychain.(Citation: Koi Glassworm New Tricks December 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9f2a884d-0974-4080-80a1-13a29a7f25c7`.
