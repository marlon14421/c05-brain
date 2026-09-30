---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0251"
target_object: "T1056.004"
stix_relationship_id: "relationship--4f550078-32b1-4abb-aa90-0e9fb7cc45f9"
---
# Relationship 6739: S0251 — uses → T1056.004

**Source object:** [[01 ATT&CK/S0251 - Zebrocy|S0251: Zebrocy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.004 - Credential API Hooking|T1056.004: Credential API Hooking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Zebrocy](https://attack.mitre.org/software/S0251) installs an application-defined Windows hook to get notified when a network drive has been attached, so it can then use the hook to call its RecordToFile file stealing method.(Citation: Securelist Sofacy Feb 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f550078-32b1-4abb-aa90-0e9fb7cc45f9`.
