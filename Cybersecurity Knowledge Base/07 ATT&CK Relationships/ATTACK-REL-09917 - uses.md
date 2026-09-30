---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1056"
target_object: "T1583.004"
stix_relationship_id: "relationship--cbdf3215-ec7c-4d45-ac64-583870d07cc6"
---
# Relationship 9917: G1056 — uses → T1583.004

**Source object:** [[01 ATT&CK/G1056 - TeamPCP|G1056: TeamPCP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.004 - Server|T1583.004: Server]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP](https://attack.mitre.org/groups/G1056) has leased infrastructure specifically for offensive operations including Google assets in AS396982.(Citation: Hunt.io TeamPCP Toolkit MAY 2026)(Citation: FBI TeamPCP JUL 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cbdf3215-ec7c-4d45-ac64-583870d07cc6`.
