---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0039"
target_object: "T1003"
stix_relationship_id: "relationship--a0c55c8d-6192-4faa-a5a2-1742fb5815a0"
---
# Relationship 6437: G0039 — uses → T1003

**Source object:** [[01 ATT&CK/G0039 - Suckfly|G0039: Suckfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003 - OS Credential Dumping|T1003: OS Credential Dumping]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Suckfly](https://attack.mitre.org/groups/G0039) used a signed credential-dumping tool to obtain victim account credentials.(Citation: Symantec Suckfly May 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a0c55c8d-6192-4faa-a5a2-1742fb5815a0`.
