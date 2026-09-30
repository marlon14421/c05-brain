---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0027"
target_object: "T1133"
stix_relationship_id: "relationship--bbb92214-8772-4e46-916b-2d9c0cdec83e"
---
# Relationship 9719: C0027 — uses → T1133

**Source object:** [[01 ATT&CK/C0027 - C0027|C0027: C0027]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1133 - External Remote Services|T1133: External Remote Services]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0027](https://attack.mitre.org/campaigns/C0027), [Scattered Spider](https://attack.mitre.org/groups/G1015) used Citrix and VPNs to persist in compromised environments.(Citation: Crowdstrike TELCO BPO Campaign December 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bbb92214-8772-4e46-916b-2d9c0cdec83e`.
