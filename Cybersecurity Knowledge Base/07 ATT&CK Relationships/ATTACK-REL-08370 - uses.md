---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0335"
target_object: "T1016"
stix_relationship_id: "relationship--45f5f01e-cfdd-4212-8bd6-0c1b0c82a0a2"
---
# Relationship 8370: S0335 — uses → T1016

**Source object:** [[01 ATT&CK/S0335 - Carbon|S0335: Carbon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carbon](https://attack.mitre.org/software/S0335) can collect the IP address of the victims and other computers on the network using the commands: ipconfig -all nbtstat -n , and nbtstat -s .(Citation: ESET Carbon Mar 2017)(Citation: GovCERT Carbon May 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45f5f01e-cfdd-4212-8bd6-0c1b0c82a0a2`.
