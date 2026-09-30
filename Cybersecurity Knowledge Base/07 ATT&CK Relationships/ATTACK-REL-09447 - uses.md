---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0447"
target_object: "T1056.001"
stix_relationship_id: "relationship--6494b2d2-8f8f-4e81-886c-dadd57df6edc"
---
# Relationship 9447: S0447 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0447 - Lokibot|S0447: Lokibot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lokibot](https://attack.mitre.org/software/S0447) has the ability to capture input on the compromised host via keylogging.(Citation: FSecure Lokibot November 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6494b2d2-8f8f-4e81-886c-dadd57df6edc`.
