---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0147"
target_object: "T1074.001"
stix_relationship_id: "relationship--c93bb2b9-bd22-4e14-b884-2141168387b2"
---
# Relationship 7430: S0147 — uses → T1074.001

**Source object:** [[01 ATT&CK/S0147 - Pteranodon|S0147: Pteranodon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pteranodon](https://attack.mitre.org/software/S0147) creates various subdirectories under %Temp%\reports\% and copies files to those subdirectories. It also creates a folder at C:\Users\ \AppData\Roaming\Microsoft\store to store screenshot JPEG files.(Citation: Palo Alto Gamaredon Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c93bb2b9-bd22-4e14-b884-2141168387b2`.
