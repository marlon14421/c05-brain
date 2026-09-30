---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0681"
target_object: "T1003.001"
stix_relationship_id: "relationship--58b1c6e7-5481-4162-a90c-0b7122c3680d"
---
# Relationship 4270: S0681 — uses → T1003.001

**Source object:** [[01 ATT&CK/S0681 - Lizar|S0681: Lizar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lizar](https://attack.mitre.org/software/S0681) can run [Mimikatz](https://attack.mitre.org/software/S0002) to harvest credentials.(Citation: Threatpost Lizar May 2021)(Citation: BiZone Lizar May 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--58b1c6e7-5481-4162-a90c-0b7122c3680d`.
