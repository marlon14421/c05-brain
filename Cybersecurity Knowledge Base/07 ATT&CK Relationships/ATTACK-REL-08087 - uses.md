---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0115"
target_object: "T1497.003"
stix_relationship_id: "relationship--53f5aaf3-b4de-4e31-bf50-a297bb8b61ca"
---
# Relationship 8087: S0115 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0115 - Crimson|S0115: Crimson]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Crimson](https://attack.mitre.org/software/S0115) can determine when it has been installed on a host for at least 15 days before downloading the final payload.(Citation: Proofpoint Operation Transparent Tribe March 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--53f5aaf3-b4de-4e31-bf50-a297bb8b61ca`.
