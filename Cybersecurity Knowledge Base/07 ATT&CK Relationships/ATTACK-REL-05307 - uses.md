---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0457"
target_object: "T1059.003"
stix_relationship_id: "relationship--5ff771c3-7d1c-4d04-a81e-76e374951e72"
---
# Relationship 5307: S0457 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0457 - Netwalker|S0457: Netwalker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Operators deploying [Netwalker](https://attack.mitre.org/software/S0457) have used batch scripts to retrieve the [Netwalker](https://attack.mitre.org/software/S0457) payload.(Citation: Sophos Netwalker May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5ff771c3-7d1c-4d04-a81e-76e374951e72`.
