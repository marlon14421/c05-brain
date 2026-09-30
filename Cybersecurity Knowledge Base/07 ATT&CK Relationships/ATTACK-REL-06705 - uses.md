---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1133"
target_object: "T1529"
stix_relationship_id: "relationship--6a8c7cab-bdf7-43dc-960b-84f47767f2df"
---
# Relationship 6705: S1133 — uses → T1529

**Source object:** [[01 ATT&CK/S1133 - Apostle|S1133: Apostle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1529 - System Shutdown-Reboot|T1529: System Shutdown/Reboot]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Apostle](https://attack.mitre.org/software/S1133) reboots the victim machine following wiping and related activity.(Citation: SentinelOne Agrius 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6a8c7cab-bdf7-43dc-960b-84f47767f2df`.
