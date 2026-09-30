---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0232"
target_object: "T1059.003"
stix_relationship_id: "relationship--fc3ec682-31cc-4e74-8d04-a5fdef9e8410"
---
# Relationship 6784: S0232 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0232 - HOMEFRY|S0232: HOMEFRY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HOMEFRY](https://attack.mitre.org/software/S0232) uses a command-line interface.(Citation: FireEye Periscope March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc3ec682-31cc-4e74-8d04-a5fdef9e8410`.
