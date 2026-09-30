---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1065"
target_object: "T1566.001"
stix_relationship_id: "relationship--9e92ab98-b547-4206-8158-a186f7570550"
---
# Relationship 7499: S1065 — uses → T1566.001

**Source object:** [[01 ATT&CK/S1065 - Woody RAT|S1065: Woody RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Woody RAT](https://attack.mitre.org/software/S1065) has been delivered via malicious Word documents and archive files.(Citation: MalwareBytes WoodyRAT Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e92ab98-b547-4206-8158-a186f7570550`.
