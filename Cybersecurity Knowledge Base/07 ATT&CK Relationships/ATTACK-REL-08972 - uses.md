---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0142"
target_object: "T1566.001"
stix_relationship_id: "relationship--6c4c4e5d-0641-4441-a5aa-d27f3362811f"
---
# Relationship 8972: G0142 — uses → T1566.001

**Source object:** [[01 ATT&CK/G0142 - Confucius|G0142: Confucius]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Confucius](https://attack.mitre.org/groups/G0142) has crafted and sent victims malicious attachments to gain initial access.(Citation: Uptycs Confucius APT Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c4c4e5d-0641-4441-a5aa-d27f3362811f`.
