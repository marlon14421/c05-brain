---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1553.005"
stix_relationship_id: "relationship--a05a823c-de82-43ec-b235-4f09e0527811"
---
# Relationship 2680: S0650 — uses → T1553.005

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.005 - Mark-of-the-Web Bypass|T1553.005: Mark-of-the-Web Bypass]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) has been packaged in ISO files in order to bypass Mark of the Web (MOTW) security measures.(Citation: Trend Micro Black Basta October 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a05a823c-de82-43ec-b235-4f09e0527811`.
