---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9010"
target_object: "T1213.003"
stix_relationship_id: "relationship--45e23658-bbbb-46ff-a1f3-ad370c2a3ad5"
---
# Relationship 8424: S9010 — uses → T1213.003

**Source object:** [[01 ATT&CK/S9010 - GlassWorm|S9010: GlassWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1213.003 - Code Repositories|T1213.003: Code Repositories]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) has gathered code repository authentication materials for NPM and GitHub.(Citation: Koi Glassworm New Tricks December 2025)(Citation: Koi Glassworm InvisibleCode October 2025)(Citation: Socket GlassWorm January 2026) [GlassWorm](https://attack.mitre.org/software/S9010) has collected details pertaining to the npm configuration data for `_authToken`.(Citation: Koi Glassworm InvisibleCode October 2025)(Citation: Socket GlassWorm January 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45e23658-bbbb-46ff-a1f3-ad370c2a3ad5`.
