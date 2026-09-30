---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0021"
target_object: "T1055.001"
stix_relationship_id: "relationship--7fd4fe68-0f2a-485c-9b10-6847428ef5da"
---
# Relationship 9824: S0021 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0021 - Derusbi|S0021: Derusbi]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Derusbi](https://attack.mitre.org/software/S0021) injects itself into the secure shell (SSH) process.(Citation: Airbus Derusbi 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7fd4fe68-0f2a-485c-9b10-6847428ef5da`.
