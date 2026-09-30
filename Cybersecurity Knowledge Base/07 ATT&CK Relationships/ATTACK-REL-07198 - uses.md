---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0341"
target_object: "T1046"
stix_relationship_id: "relationship--9409dcff-0ddf-43f6-b7c0-937fd9216ee0"
---
# Relationship 7198: S0341 — uses → T1046

**Source object:** [[01 ATT&CK/S0341 - Xbash|S0341: Xbash]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Xbash](https://attack.mitre.org/software/S0341) can perform port scanning of TCP and UDP ports.(Citation: Unit42 Xbash Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9409dcff-0ddf-43f6-b7c0-937fd9216ee0`.
