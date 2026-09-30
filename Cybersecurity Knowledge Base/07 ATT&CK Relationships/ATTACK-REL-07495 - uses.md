---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1075"
target_object: "T1041"
stix_relationship_id: "relationship--a5931b14-3087-4fc5-8167-498fc1af23f1"
---
# Relationship 7495: S1075 — uses → T1041

**Source object:** [[01 ATT&CK/S1075 - KOPILUWAK|S1075: KOPILUWAK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KOPILUWAK](https://attack.mitre.org/software/S1075) has exfiltrated collected data to its C2 via POST requests.(Citation: Mandiant Suspected Turla Campaign February 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a5931b14-3087-4fc5-8167-498fc1af23f1`.
