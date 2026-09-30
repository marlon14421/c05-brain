---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0011"
target_object: "T1566.001"
stix_relationship_id: "relationship--844a2a38-68aa-45ed-8fa8-4854500cb63d"
---
# Relationship 9542: C0011 — uses → T1566.001

**Source object:** [[01 ATT&CK/C0011 - C0011|C0011: C0011]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0011](https://attack.mitre.org/campaigns/C0011), [Transparent Tribe](https://attack.mitre.org/groups/G0134) sent malicious attachments via email to student targets in India.(Citation: Cisco Talos Transparent Tribe Education Campaign July 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--844a2a38-68aa-45ed-8fa8-4854500cb63d`.
