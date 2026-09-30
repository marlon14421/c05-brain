---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9010"
target_object: "T1555.001"
stix_relationship_id: "relationship--354b2d56-9b68-4481-b05d-b72a347bb4a7"
---
# Relationship 6245: S9010 — uses → T1555.001

**Source object:** [[01 ATT&CK/S9010 - GlassWorm|S9010: GlassWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.001 - Keychain|T1555.001: Keychain]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) has collected keys stored within `/Library/Keychains/login.keychain-db`.(Citation: Koi Glassworm New Tricks December 2025)(Citation: Socket GlassWorm January 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--354b2d56-9b68-4481-b05d-b72a347bb4a7`.
