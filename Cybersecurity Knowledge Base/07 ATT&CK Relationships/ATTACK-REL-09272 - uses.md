---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0084"
target_object: "T1136.001"
stix_relationship_id: "relationship--7e55e411-230e-4d1a-a780-d07784ed2cd6"
---
# Relationship 9272: S0084 — uses → T1136.001

**Source object:** [[01 ATT&CK/S0084 - Mis-Type|S0084: Mis-Type]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1136.001 - Local Account|T1136.001: Local Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mis-Type](https://attack.mitre.org/software/S0084) may create a temporary user on the system named `Lost_{Unique Identifier}`.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e55e411-230e-4d1a-a780-d07784ed2cd6`.
