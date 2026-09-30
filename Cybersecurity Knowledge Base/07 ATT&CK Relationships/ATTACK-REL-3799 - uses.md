---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1145"
target_object: "T1027.003"
stix_relationship_id: "relationship--96a0df58-61cc-4380-aaba-e05207c39673"
---
# Relationship 3799: S1145 — uses → T1027.003

**Source object:** [[01 ATT&CK/S1145 - Pikabot|S1145: Pikabot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.003 - Steganography|T1027.003: Steganography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pikabot](https://attack.mitre.org/software/S1145) loads a set of PNG images stored in the malware's resources section (RCDATA), each with an encrypted section containing portions of the core [Pikabot](https://attack.mitre.org/software/S1145) core module. These sections are loaded and decrypted using a bitwise XOR operation with a hardcoded 32 bit key.(Citation: Zscaler Pikabot 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--96a0df58-61cc-4380-aaba-e05207c39673`.
