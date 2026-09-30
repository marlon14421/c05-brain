---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0027"
target_object: "T1021.006"
stix_relationship_id: "relationship--df8350d6-a7a7-421d-a9e8-64d7e0cc0653"
---
# Relationship 9373: G0027 — uses → T1021.006

**Source object:** [[01 ATT&CK/G0027 - Threat Group-3390|G0027: Threat Group-3390]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.006 - Windows Remote Management|T1021.006: Windows Remote Management]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Threat Group-3390](https://attack.mitre.org/groups/G0027) has used WinRM to enable remote execution.(Citation: SecureWorks BRONZE UNION June 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--df8350d6-a7a7-421d-a9e8-64d7e0cc0653`.
