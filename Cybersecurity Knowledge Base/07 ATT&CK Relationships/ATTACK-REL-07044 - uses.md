---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0027"
target_object: "T1608.004"
stix_relationship_id: "relationship--7acc1226-d784-448e-8aeb-7f58e343c4da"
---
# Relationship 7044: G0027 — uses → T1608.004

**Source object:** [[01 ATT&CK/G0027 - Threat Group-3390|G0027: Threat Group-3390]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.004 - Drive-by Target|T1608.004: Drive-by Target]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Threat Group-3390](https://attack.mitre.org/groups/G0027) has embedded malicious code into websites to screen a potential victim's IP address and then exploit their browser if they are of interest.(Citation: Gallagher 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7acc1226-d784-448e-8aeb-7f58e343c4da`.
