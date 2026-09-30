---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0476"
target_object: "T1566.001"
stix_relationship_id: "relationship--7e9f9565-d9c5-47e5-a962-8dfa3dc77fc6"
---
# Relationship 9515: S0476 — uses → T1566.001

**Source object:** [[01 ATT&CK/S0476 - Valak|S0476: Valak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Valak](https://attack.mitre.org/software/S0476) has been delivered via spearphishing e-mails with password protected ZIP files.(Citation: Unit 42 Valak July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e9f9565-d9c5-47e5-a962-8dfa3dc77fc6`.
