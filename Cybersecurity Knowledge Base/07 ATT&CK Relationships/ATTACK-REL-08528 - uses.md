---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0395"
target_object: "T1029"
stix_relationship_id: "relationship--20c556ad-adcd-4b60-bde1-c3eff06c0593"
---
# Relationship 8528: S0395 — uses → T1029

**Source object:** [[01 ATT&CK/S0395 - LightNeuron|S0395: LightNeuron]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1029 - Scheduled Transfer|T1029: Scheduled Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LightNeuron](https://attack.mitre.org/software/S0395) can be configured to exfiltrate data during nighttime or working hours.(Citation: ESET LightNeuron May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--20c556ad-adcd-4b60-bde1-c3eff06c0593`.
