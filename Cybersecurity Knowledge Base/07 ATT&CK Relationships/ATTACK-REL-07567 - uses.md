---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0395"
target_object: "T1106"
stix_relationship_id: "relationship--abf45442-6ca3-4538-ad21-db2e46f43f67"
---
# Relationship 7567: S0395 — uses → T1106

**Source object:** [[01 ATT&CK/S0395 - LightNeuron|S0395: LightNeuron]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LightNeuron](https://attack.mitre.org/software/S0395) is capable of starting a process using CreateProcess.(Citation: ESET LightNeuron May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--abf45442-6ca3-4538-ad21-db2e46f43f67`.
