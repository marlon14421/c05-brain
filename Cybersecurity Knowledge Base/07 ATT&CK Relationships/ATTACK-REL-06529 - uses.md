---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1003"
target_object: "T1505.003"
stix_relationship_id: "relationship--6ecd9294-8818-4de9-a871-38d514380bd8"
---
# Relationship 6529: G1003 — uses → T1505.003

**Source object:** [[01 ATT&CK/G1003 - Ember Bear|G1003: Ember Bear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ember Bear](https://attack.mitre.org/groups/G1003) deploys web shells following initial access for either follow-on command execution or protocol tunneling. Example web shells used by [Ember Bear](https://attack.mitre.org/groups/G1003) include P0wnyshell, reGeorg, [P.A.S. Webshell](https://attack.mitre.org/software/S0598), and custom variants of publicly-available web shell examples.(Citation: Cadet Blizzard emerges as novel threat actor)(Citation: CISA GRU29155 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6ecd9294-8818-4de9-a871-38d514380bd8`.
