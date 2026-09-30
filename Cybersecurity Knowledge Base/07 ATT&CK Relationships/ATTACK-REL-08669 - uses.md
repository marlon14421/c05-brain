---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0395"
target_object: "T1020"
stix_relationship_id: "relationship--2b1fb532-84e3-4f77-962c-038c798d239e"
---
# Relationship 8669: S0395 — uses → T1020

**Source object:** [[01 ATT&CK/S0395 - LightNeuron|S0395: LightNeuron]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1020 - Automated Exfiltration|T1020: Automated Exfiltration]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LightNeuron](https://attack.mitre.org/software/S0395) can be configured to automatically exfiltrate files under a specified directory.(Citation: ESET LightNeuron May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b1fb532-84e3-4f77-962c-038c798d239e`.
