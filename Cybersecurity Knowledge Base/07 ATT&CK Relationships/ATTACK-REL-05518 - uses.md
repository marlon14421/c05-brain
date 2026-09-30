---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0069"
target_object: "T1204.001"
stix_relationship_id: "relationship--b6fa5f7f-1055-4a9a-8372-d281fd6ca4af"
---
# Relationship 5518: G0069 — uses → T1204.001

**Source object:** [[01 ATT&CK/G0069 - MuddyWater|G0069: MuddyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MuddyWater](https://attack.mitre.org/groups/G0069) has distributed URLs in phishing e-mails that link to lure documents.(Citation: Anomali Static Kitten February 2021)(Citation: Trend Micro Muddy Water March 2021)(Citation: Proofpoint TA450 Phishing March 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b6fa5f7f-1055-4a9a-8372-d281fd6ca4af`.
