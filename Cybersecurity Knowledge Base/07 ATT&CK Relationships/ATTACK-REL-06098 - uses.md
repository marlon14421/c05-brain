---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0010"
target_object: "T1584.001"
stix_relationship_id: "relationship--57e9b366-fac5-4320-bb76-da81953de2dc"
---
# Relationship 6098: C0010 — uses → T1584.001

**Source object:** [[01 ATT&CK/C0010 - C0010|C0010: C0010]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.001 - Domains|T1584.001: Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0010](https://attack.mitre.org/campaigns/C0010), UNC3890 actors likely compromised the domain of a legitimate Israeli shipping company.(Citation: Mandiant UNC3890 Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--57e9b366-fac5-4320-bb76-da81953de2dc`.
