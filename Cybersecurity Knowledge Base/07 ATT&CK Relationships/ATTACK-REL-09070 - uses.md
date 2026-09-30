---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0029"
target_object: "T1071.004"
stix_relationship_id: "relationship--4f27c041-e965-4ee3-b47c-6681e7fc1ace"
---
# Relationship 9070: C0029 — uses → T1071.004

**Source object:** [[01 ATT&CK/C0029 - Cutting Edge|C0029: Cutting Edge]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Cutting Edge](https://attack.mitre.org/campaigns/C0029), threat actors used DNS to tunnel IPv4 C2 traffic.(Citation: Mandiant Cutting Edge Part 2 January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f27c041-e965-4ee3-b47c-6681e7fc1ace`.
