---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0131"
target_object: "T1003"
stix_relationship_id: "relationship--6e43af09-b4bb-46dc-87f3-e2b72e70b47a"
---
# Relationship 5608: G0131 — uses → T1003

**Source object:** [[01 ATT&CK/G0131 - Tonto Team|G0131: Tonto Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003 - OS Credential Dumping|T1003: OS Credential Dumping]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tonto Team](https://attack.mitre.org/groups/G0131) has used a variety of credential dumping tools.(Citation: TrendMicro Tonto Team October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e43af09-b4bb-46dc-87f3-e2b72e70b47a`.
