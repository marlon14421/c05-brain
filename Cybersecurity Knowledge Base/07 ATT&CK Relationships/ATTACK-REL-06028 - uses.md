---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0336"
target_object: "T1016"
stix_relationship_id: "relationship--14fe92e6-9a5e-4116-8316-e52f6270b02c"
---
# Relationship 6028: S0336 — uses → T1016

**Source object:** [[01 ATT&CK/S0336 - NanoCore|S0336: NanoCore]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NanoCore](https://attack.mitre.org/software/S0336) gathers the IP address from the victim’s machine.(Citation: DigiTrust NanoCore Jan 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--14fe92e6-9a5e-4116-8316-e52f6270b02c`.
