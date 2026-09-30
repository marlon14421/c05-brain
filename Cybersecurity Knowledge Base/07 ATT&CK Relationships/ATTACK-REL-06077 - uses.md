---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0106"
target_object: "T1082"
stix_relationship_id: "relationship--745106bb-3641-488e-ae1c-547cd6ea9b7a"
---
# Relationship 6077: S0106 — uses → T1082

**Source object:** [[01 ATT&CK/S0106 - cmd|S0106: cmd]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[cmd](https://attack.mitre.org/software/S0106) can be used to find information about the operating system.(Citation: TechNet Dir)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--745106bb-3641-488e-ae1c-547cd6ea9b7a`.
