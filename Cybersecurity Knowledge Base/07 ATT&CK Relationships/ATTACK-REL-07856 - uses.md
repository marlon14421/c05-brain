---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0664"
target_object: "T1205"
stix_relationship_id: "relationship--8f27fb1d-f888-4167-a08c-781dde29755d"
---
# Relationship 7856: S0664 — uses → T1205

**Source object:** [[01 ATT&CK/S0664 - Pandora|S0664: Pandora]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1205 - Traffic Signaling|T1205: Traffic Signaling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pandora](https://attack.mitre.org/software/S0664) can identify if incoming HTTP traffic contains a token and if so it will intercept the traffic and process the received command.(Citation: Trend Micro Iron Tiger April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f27fb1d-f888-4167-a08c-781dde29755d`.
