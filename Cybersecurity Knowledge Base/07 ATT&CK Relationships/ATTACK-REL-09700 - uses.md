---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0021"
target_object: "T1583.001"
stix_relationship_id: "relationship--07ef3f89-c78a-4aa0-a77e-842c5220244b"
---
# Relationship 9700: C0021 — uses → T1583.001

**Source object:** [[01 ATT&CK/C0021 - C0021|C0021: C0021]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [C0021](https://attack.mitre.org/campaigns/C0021), the threat actors registered domains for use in C2.(Citation: FireEye APT29 Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--07ef3f89-c78a-4aa0-a77e-842c5220244b`.
