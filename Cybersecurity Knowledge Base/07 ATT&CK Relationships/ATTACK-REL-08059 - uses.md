---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0080"
target_object: "T1588.002"
stix_relationship_id: "relationship--7363ed1a-6f75-4ded-9179-2fdba17f6cf1"
---
# Relationship 8059: G0080 — uses → T1588.002

**Source object:** [[01 ATT&CK/G0080 - Cobalt Group|G0080: Cobalt Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobalt Group](https://attack.mitre.org/groups/G0080) has obtained and used a variety of tools including [Mimikatz](https://attack.mitre.org/software/S0002), [PsExec](https://attack.mitre.org/software/S0029), [Cobalt Strike](https://attack.mitre.org/software/S0154), and [SDelete](https://attack.mitre.org/software/S0195).(Citation: PTSecurity Cobalt Dec 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7363ed1a-6f75-4ded-9179-2fdba17f6cf1`.
