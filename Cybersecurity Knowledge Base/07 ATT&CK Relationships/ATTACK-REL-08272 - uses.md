---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0030"
target_object: "T1588.002"
stix_relationship_id: "relationship--8ff5abd9-8bbe-4fab-8001-23b2973c0764"
---
# Relationship 8272: G0030 — uses → T1588.002

**Source object:** [[01 ATT&CK/G0030 - Lotus Blossom|G0030: Lotus Blossom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lotus Blossom](https://attack.mitre.org/groups/G0030) has used publicly-available tools such as a Python-based cookie stealer for Chrome browsers, [Impacket](https://attack.mitre.org/software/S0357), and the Venom proxy tool.(Citation: Cisco LotusBlossom 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8ff5abd9-8bbe-4fab-8001-23b2973c0764`.
