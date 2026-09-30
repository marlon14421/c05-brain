---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0683"
target_object: "T1610"
stix_relationship_id: "relationship--71d8ce83-3410-4bf2-b30c-a3aa4c8a931d"
---
# Relationship 7827: S0683 — uses → T1610

**Source object:** [[01 ATT&CK/S0683 - Peirates|S0683: Peirates]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1610 - Deploy Container|T1610: Deploy Container]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Peirates](https://attack.mitre.org/software/S0683) can deploy a pod that mounts its node’s root file system, then execute a command to create a reverse shell on the node.(Citation: Peirates GitHub)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71d8ce83-3410-4bf2-b30c-a3aa4c8a931d`.
