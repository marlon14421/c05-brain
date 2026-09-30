---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1542.003"
stix_relationship_id: "relationship--9e90e4a5-844c-4516-9044-6f35bbf27806"
---
# Relationship 6940: G0007 — uses → T1542.003

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1542.003 - Bootkit|T1542.003: Bootkit]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has deployed a bootkit along with [Downdelph](https://attack.mitre.org/software/S0134) to ensure its persistence on the victim. The bootkit shares code with some variants of [BlackEnergy](https://attack.mitre.org/software/S0089).(Citation: ESET Sednit Part 3)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e90e4a5-844c-4516-9044-6f35bbf27806`.
