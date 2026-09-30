---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0172"
target_object: "T1082"
stix_relationship_id: "relationship--edbd751e-29ad-419f-a3ff-9d210453351d"
---
# Relationship 7369: S0172 — uses → T1082

**Source object:** [[01 ATT&CK/S0172 - Reaver|S0172: Reaver]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Reaver](https://attack.mitre.org/software/S0172) collects system information from the victim, including CPU speed, computer name, ANSI code page, OEM code page identifier for the OS, Microsoft Windows version, and memory information.(Citation: Palo Alto Reaver Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--edbd751e-29ad-419f-a3ff-9d210453351d`.
