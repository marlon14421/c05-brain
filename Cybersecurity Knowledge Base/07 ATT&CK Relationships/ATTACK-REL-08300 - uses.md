---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0572"
target_object: "T1059.003"
stix_relationship_id: "relationship--6188b02d-e7cb-417a-9093-e2d2eea5883f"
---
# Relationship 8300: S0572 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0572 - Caterpillar WebShell|S0572: Caterpillar WebShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Caterpillar WebShell](https://attack.mitre.org/software/S0572) can run commands on the compromised asset with CMD functions.(Citation: ClearSky Lebanese Cedar Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6188b02d-e7cb-417a-9093-e2d2eea5883f`.
