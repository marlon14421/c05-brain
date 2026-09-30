---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0013"
target_object: "T1204.002"
stix_relationship_id: "relationship--d7836be5-6c99-4a14-90ca-e342455516ab"
---
# Relationship 7176: C0013 — uses → T1204.002

**Source object:** [[01 ATT&CK/C0013 - Operation Sharpshooter|C0013: Operation Sharpshooter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Operation Sharpshooter](https://attack.mitre.org/campaigns/C0013), the threat actors relied on victims executing malicious Microsoft Word or PDF files.(Citation: McAfee Sharpshooter December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d7836be5-6c99-4a14-90ca-e342455516ab`.
