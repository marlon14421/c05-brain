---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0268"
target_object: "T1041"
stix_relationship_id: "relationship--b16afb1a-b6ee-4cfb-9fb1-966478828480"
---
# Relationship 7432: S0268 — uses → T1041

**Source object:** [[01 ATT&CK/S0268 - Bisonal|S0268: Bisonal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bisonal](https://attack.mitre.org/software/S0268) has added the exfiltrated data to the URL over the C2 channel.(Citation: Talos Bisonal Mar 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b16afb1a-b6ee-4cfb-9fb1-966478828480`.
