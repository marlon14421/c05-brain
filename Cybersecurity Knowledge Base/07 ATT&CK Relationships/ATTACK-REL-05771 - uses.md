---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0018"
target_object: "T1204.002"
stix_relationship_id: "relationship--e752cfb4-7865-4590-b355-eb1f1b851c5e"
---
# Relationship 5771: G0018 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0018 - admin@338|G0018: admin@338]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[admin@338](https://attack.mitre.org/groups/G0018) has attempted to get victims to launch malicious Microsoft Word attachments delivered via spearphishing emails.(Citation: FireEye admin@338)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e752cfb4-7865-4590-b355-eb1f1b851c5e`.
