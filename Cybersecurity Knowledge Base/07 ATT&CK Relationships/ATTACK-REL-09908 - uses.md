---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0154"
target_object: "T1059.003"
stix_relationship_id: "relationship--fc901b6f-3575-443c-9ba3-32ca1bebf7af"
---
# Relationship 9908: S0154 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobalt Strike](https://attack.mitre.org/software/S0154) uses a command-line interface to interact with systems.(Citation: Cobalt Strike TTPs Dec 2017)(Citation: Talos Cobalt Strike September 2020)(Citation: Cobalt Strike Manual 4.3 November 2020)(Citation: Trend Micro Black Basta October 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc901b6f-3575-443c-9ba3-32ca1bebf7af`.
