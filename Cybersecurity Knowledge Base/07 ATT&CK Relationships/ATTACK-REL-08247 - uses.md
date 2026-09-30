---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1051"
target_object: "T1090.003"
stix_relationship_id: "relationship--6066869c-5883-457f-bf48-10f453039b94"
---
# Relationship 8247: G1051 — uses → T1090.003

**Source object:** [[01 ATT&CK/G1051 - Medusa Group|G1051: Medusa Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Medusa Group](https://attack.mitre.org/groups/G1051) has used TOR nodes for communications.(Citation: Palo Alto Unit 42 Medusa Group Medusa Ransomware January 2024)(Citation: Check Point Medusa Ransomware April 2025)(Citation: Broadcom Medusa Ransomware Medusa Group March 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6066869c-5883-457f-bf48-10f453039b94`.
