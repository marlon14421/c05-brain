---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9020"
target_object: "T1082"
stix_relationship_id: "relationship--83b6ef41-24e7-4ace-bb6e-29faf8ac5ab4"
---
# Relationship 3200: S9020 — uses → T1082

**Source object:** [[01 ATT&CK/S9020 - LODEINFO|S9020: LODEINFO]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LODEINFO](https://attack.mitre.org/software/S9020) can disover machine information including OS architecture, the ANSI code page (ACP) identifier, and hostname.(Citation: Kaspersky LODEINFO Part II OCT 2022)(Citation: ITOCHU LODEINFO JAN 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--83b6ef41-24e7-4ace-bb6e-29faf8ac5ab4`.
