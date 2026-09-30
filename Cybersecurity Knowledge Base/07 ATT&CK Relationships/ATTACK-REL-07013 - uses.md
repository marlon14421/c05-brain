---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0336"
target_object: "T1056.001"
stix_relationship_id: "relationship--a09b9e3f-96b8-4fde-9f7d-261b449cdabd"
---
# Relationship 7013: S0336 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0336 - NanoCore|S0336: NanoCore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NanoCore](https://attack.mitre.org/software/S0336) can perform keylogging on the victim’s machine.(Citation: PaloAlto NanoCore Feb 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a09b9e3f-96b8-4fde-9f7d-261b449cdabd`.
