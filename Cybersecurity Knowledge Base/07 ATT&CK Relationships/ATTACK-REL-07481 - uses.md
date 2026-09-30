---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0395"
target_object: "T1071.003"
stix_relationship_id: "relationship--12918fb6-9b92-4644-a4c2-4f2f471e9b2c"
---
# Relationship 7481: S0395 — uses → T1071.003

**Source object:** [[01 ATT&CK/S0395 - LightNeuron|S0395: LightNeuron]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.003 - Mail Protocols|T1071.003: Mail Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LightNeuron](https://attack.mitre.org/software/S0395) uses SMTP for C2.(Citation: ESET LightNeuron May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--12918fb6-9b92-4644-a4c2-4f2f471e9b2c`.
