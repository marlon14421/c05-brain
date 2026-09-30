---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1239"
target_object: "T1560.001"
stix_relationship_id: "relationship--ff1715e6-2b65-47a3-86f2-d5d09f2e31e4"
---
# Relationship 2852: S1239 — uses → T1560.001

**Source object:** [[01 ATT&CK/S1239 - TONESHELL|S1239: TONESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TONESHELL](https://attack.mitre.org/software/S1239) used WinRAR rar.exe to archive files for exfiltration.(Citation: Palo Alto Unit42 STATELY TAURUS TONESHELL September 2023)(Citation: Unit42 Chinese VSCode 06 September 2024) [TONESHELL](https://attack.mitre.org/software/S1239) has also utilized a unique 13-character password consisting of upper lower case and digits to protect RAR archives.(Citation: Unit42 Chinese VSCode 06 September 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ff1715e6-2b65-47a3-86f2-d5d09f2e31e4`.
