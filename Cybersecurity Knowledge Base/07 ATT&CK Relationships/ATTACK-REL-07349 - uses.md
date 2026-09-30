---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0194"
target_object: "T1574.009"
stix_relationship_id: "relationship--2e202038-196d-41c7-8fdf-27b4fcf88830"
---
# Relationship 7349: S0194 — uses → T1574.009

**Source object:** [[01 ATT&CK/S0194 - PowerSploit|S0194: PowerSploit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.009 - Path Interception by Unquoted Path|T1574.009: Path Interception by Unquoted Path]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerSploit](https://attack.mitre.org/software/S0194) contains a collection of Privesc-PowerUp modules that can discover and exploit unquoted path vulnerabilities.(Citation: GitHub PowerSploit May 2012)(Citation: PowerSploit Documentation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e202038-196d-41c7-8fdf-27b4fcf88830`.
