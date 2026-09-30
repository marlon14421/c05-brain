---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0281"
target_object: "T1543.001"
stix_relationship_id: "relationship--4065a71f-ae1b-4dfc-9825-56d2af6d589c"
---
# Relationship 9854: S0281 — uses → T1543.001

**Source object:** [[01 ATT&CK/S0281 - Dok|S0281: Dok]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.001 - Launch Agent|T1543.001: Launch Agent]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dok](https://attack.mitre.org/software/S0281) installs two LaunchAgents to redirect all network traffic with a randomly generated name for each plist file maintaining the format com.random.name.plist .(Citation: objsee mac malware 2017)(Citation: CheckPoint Dok)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4065a71f-ae1b-4dfc-9825-56d2af6d589c`.
