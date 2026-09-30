---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0482"
target_object: "T1222.002"
stix_relationship_id: "relationship--f19f6015-ffbe-4998-ad82-403fcfc2e649"
---
# Relationship 9973: S0482 — uses → T1222.002

**Source object:** [[01 ATT&CK/S0482 - Bundlore|S0482: Bundlore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1222.002 - Linux and Mac Permissions|T1222.002: Linux and Mac Permissions]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bundlore](https://attack.mitre.org/software/S0482) changes the permissions of a payload using the command chmod -R 755 .(Citation: 20 macOS Common Tools and Techniques)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f19f6015-ffbe-4998-ad82-403fcfc2e649`.
