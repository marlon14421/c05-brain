---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0051"
target_object: "T1021.001"
stix_relationship_id: "relationship--a48e7d01-012a-4336-9676-0f34e8501e22"
---
# Relationship 2831: G0051 — uses → T1021.001

**Source object:** [[01 ATT&CK/G0051 - FIN10|G0051: FIN10]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.001 - Remote Desktop Protocol|T1021.001: Remote Desktop Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN10](https://attack.mitre.org/groups/G0051) has used RDP to move laterally to systems in the victim environment.(Citation: FireEye FIN10 June 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a48e7d01-012a-4336-9676-0f34e8501e22`.
