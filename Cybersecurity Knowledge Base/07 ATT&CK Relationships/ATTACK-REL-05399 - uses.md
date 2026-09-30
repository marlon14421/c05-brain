---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1014"
target_object: "T1567.002"
stix_relationship_id: "relationship--03aece39-d7a2-47a4-be1a-b1d6f1d72654"
---
# Relationship 5399: G1014 — uses → T1567.002

**Source object:** [[01 ATT&CK/G1014 - LuminousMoth|G1014: LuminousMoth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LuminousMoth](https://attack.mitre.org/groups/G1014) has exfiltrated data to Google Drive.(Citation: Bitdefender LuminousMoth July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03aece39-d7a2-47a4-be1a-b1d6f1d72654`.
