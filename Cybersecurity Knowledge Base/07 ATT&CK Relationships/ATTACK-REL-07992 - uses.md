---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "S0648"
stix_relationship_id: "relationship--3f4ff91e-a279-4777-b362-a57b0c4c098b"
---
# Relationship 7992: G0046 — uses → S0648

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0648 - JSS Loader|S0648: JSS Loader]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: CrowdStrike Carbon Spider August 2021)(Citation: Microsoft Ransomware as a Service)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3f4ff91e-a279-4777-b362-a57b0c4c098b`.
