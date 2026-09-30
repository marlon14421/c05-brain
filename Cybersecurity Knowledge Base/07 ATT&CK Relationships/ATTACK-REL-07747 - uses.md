---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0268"
target_object: "T1497.003"
stix_relationship_id: "relationship--88a798b0-0820-4a6e-a9b2-416c84f3b357"
---
# Relationship 7747: S0268 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0268 - Bisonal|S0268: Bisonal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bisonal](https://attack.mitre.org/software/S0268) has checked if the malware is running in a virtual environment with the anti-debug function GetTickCount() to compare the timing.(Citation: Kaspersky CactusPete Aug 2020)(Citation: Talos Bisonal Mar 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--88a798b0-0820-4a6e-a9b2-416c84f3b357`.
