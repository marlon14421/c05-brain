---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1011"
target_object: "T1204.002"
stix_relationship_id: "relationship--736856d1-3ae3-4135-9dd4-7dfa6b55715b"
---
# Relationship 9173: G1011 — uses → T1204.002

**Source object:** [[01 ATT&CK/G1011 - EXOTIC LILY|G1011: EXOTIC LILY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[EXOTIC LILY](https://attack.mitre.org/groups/G1011) has gained execution through victims clicking on malicious LNK files contained within ISO files, which can execute hidden DLLs within the ISO.(Citation: Google EXOTIC LILY March 2022)(Citation: Proofpoint Bumblebee April 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--736856d1-3ae3-4135-9dd4-7dfa6b55715b`.
