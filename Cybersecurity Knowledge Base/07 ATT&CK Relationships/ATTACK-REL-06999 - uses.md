---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0223"
target_object: "T1053.005"
stix_relationship_id: "relationship--b853cee3-a145-407f-83fe-dd52c4efbe2f"
---
# Relationship 6999: S0223 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0223 - POWERSTATS|S0223: POWERSTATS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POWERSTATS](https://attack.mitre.org/software/S0223) has established persistence through a scheduled task using the command ”C:\Windows\system32\schtasks.exe” /Create /F /SC DAILY /ST 12:00 /TN MicrosoftEdge /TR “c:\Windows\system32\wscript.exe C:\Windows\temp\Windows.vbe” .(Citation: ClearSky MuddyWater Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b853cee3-a145-407f-83fe-dd52c4efbe2f`.
