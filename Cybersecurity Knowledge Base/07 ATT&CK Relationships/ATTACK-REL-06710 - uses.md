---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0352"
target_object: "T1543.001"
stix_relationship_id: "relationship--5a872d22-22e6-49b1-8ddd-7efc6c403ad6"
---
# Relationship 6710: S0352 — uses → T1543.001

**Source object:** [[01 ATT&CK/S0352 - OSX_OCEANLOTUS.D|S0352: OSX_OCEANLOTUS.D]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.001 - Launch Agent|T1543.001: Launch Agent]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSX_OCEANLOTUS.D](https://attack.mitre.org/software/S0352) can create a persistence file in the folder /Library/LaunchAgents .(Citation: TrendMicro MacOS April 2018)(Citation: Trend Micro MacOS Backdoor November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a872d22-22e6-49b1-8ddd-7efc6c403ad6`.
