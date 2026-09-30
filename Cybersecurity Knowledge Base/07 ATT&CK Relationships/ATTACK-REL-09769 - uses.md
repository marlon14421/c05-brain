---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0053"
target_object: "S0029"
stix_relationship_id: "relationship--7e46e7c8-e48a-4860-bbcd-224a2d12284a"
---
# Relationship 9769: G0053 — uses → S0029

**Source object:** [[01 ATT&CK/G0053 - FIN5|G0053: FIN5]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0029 - PsExec|S0029: PsExec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN5](https://attack.mitre.org/groups/G0053) uses a customized version of PsExec.(Citation: Mandiant FIN5 GrrCON Oct 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e46e7c8-e48a-4860-bbcd-224a2d12284a`.
