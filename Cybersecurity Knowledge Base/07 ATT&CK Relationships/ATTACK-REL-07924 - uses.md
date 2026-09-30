---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0077"
target_object: "T1105"
stix_relationship_id: "relationship--bdd64378-e348-4156-8490-528392c6ea82"
---
# Relationship 7924: S0077 — uses → T1105

**Source object:** [[01 ATT&CK/S0077 - CallMe|S0077: CallMe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CallMe](https://attack.mitre.org/software/S0077) has the capability to download a file to the victim from the C2 server.(Citation: Scarlet Mimic Jan 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bdd64378-e348-4156-8490-528392c6ea82`.
