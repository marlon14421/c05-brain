---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1056"
target_object: "S9042"
stix_relationship_id: "relationship--19bddbe1-af41-42d2-9e12-f301a37d35f4"
---
# Relationship 6211: G1056 — uses → S9042

**Source object:** [[01 ATT&CK/G1056 - TeamPCP|G1056: TeamPCP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S9042 - CanisterWorm|S9042: CanisterWorm]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP](https://attack.mitre.org/groups/G1056) has used [CanisterWorm](https://attack.mitre.org/software/S9042) in credential harvesting and software supply chain campaigns since at least 2026.(Citation: Aikido TeamPCP Telnyx MAR 2026)(Citation: Palo Alto TeamPCP MAR 2026)(Citation: Aikido CanisterWorm MAR 2026)(Citation: Aikido TeamPCP Trivy MAR 2026)(Citation: FBI TeamPCP JUL 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--19bddbe1-af41-42d2-9e12-f301a37d35f4`.
