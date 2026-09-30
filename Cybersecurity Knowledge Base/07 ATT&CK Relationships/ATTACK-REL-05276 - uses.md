---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0139"
target_object: "T1204.003"
stix_relationship_id: "relationship--6674eb2b-8295-4af4-b4d2-0659c15d3c71"
---
# Relationship 5276: G0139 — uses → T1204.003

**Source object:** [[01 ATT&CK/G0139 - TeamTNT|G0139: TeamTNT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.003 - Malicious Image|T1204.003: Malicious Image]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamTNT](https://attack.mitre.org/groups/G0139) has relied on users to download and execute malicious Docker images.(Citation: Lacework TeamTNT May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6674eb2b-8295-4af4-b4d2-0659c15d3c71`.
