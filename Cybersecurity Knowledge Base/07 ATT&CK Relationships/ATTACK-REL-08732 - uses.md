---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0356"
target_object: "T1566.001"
stix_relationship_id: "relationship--b23e8d31-bb6a-42b4-ab34-1c9e302a3b74"
---
# Relationship 8732: S0356 — uses → T1566.001

**Source object:** [[01 ATT&CK/S0356 - KONNI|S0356: KONNI]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KONNI](https://attack.mitre.org/software/S0356) has been delivered via spearphishing campaigns through a malicious Word document.(Citation: Malwarebytes Konni Aug 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b23e8d31-bb6a-42b4-ab34-1c9e302a3b74`.
