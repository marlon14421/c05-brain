---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1047"
target_object: "T1040"
stix_relationship_id: "relationship--4d20e130-46a0-4dbe-ac36-ea620e187770"
---
# Relationship 7531: G1047 — uses → T1040

**Source object:** [[01 ATT&CK/G1047 - Velvet Ant|G1047: Velvet Ant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1040 - Network Sniffing|T1040: Network Sniffing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Velvet Ant](https://attack.mitre.org/groups/G1047) has used a custom tool, "VELVETTAP", to perform packet capture from compromised F5 BIG-IP devices.(Citation: Sygnia VelvetAnt 2024A)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4d20e130-46a0-4dbe-ac36-ea620e187770`.
