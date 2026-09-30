---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0063"
target_object: "S1071"
stix_relationship_id: "relationship--625b01d2-1e6d-446a-8c02-e2c73b048687"
---
# Relationship 6008: C0063 — uses → S1071

**Source object:** [[01 ATT&CK/C0063 - 2025 Poland Wiper Attacks|C0063: 2025 Poland Wiper Attacks]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1071 - Rubeus|S1071: Rubeus]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2025 Poland Wiper Attacks](https://attack.mitre.org/campaigns/C0063), the adversaries used the [Rubeus](https://attack.mitre.org/software/S1071) tool to forge a Diamond Ticket that is a modified legitimate Kerberos ticket.(Citation: CERT Polska)(Citation: ESET DynoWiper Update JAN 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--625b01d2-1e6d-446a-8c02-e2c73b048687`.
