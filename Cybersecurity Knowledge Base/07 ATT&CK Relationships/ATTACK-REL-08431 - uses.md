---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9031"
target_object: "T1071.001"
stix_relationship_id: "relationship--308a7f8c-dd36-4567-9cd9-1f8232c45750"
---
# Relationship 8431: S9031 — uses → T1071.001

**Source object:** [[01 ATT&CK/S9031 - AshTag|S9031: AshTag]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AshTag](https://attack.mitre.org/software/S9031) can use HTTP to send and receive data from C2.(Citation: Palo Alto Ashen Lepus DEC 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--308a7f8c-dd36-4567-9cd9-1f8232c45750`.
