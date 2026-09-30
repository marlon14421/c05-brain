---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0054"
target_object: "T1105"
stix_relationship_id: "relationship--800825f5-6e74-43ad-a732-476fdf471225"
---
# Relationship 2696: S0054 — uses → T1105

**Source object:** [[01 ATT&CK/S0054 - CloudDuke|S0054: CloudDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CloudDuke](https://attack.mitre.org/software/S0054) downloads and executes additional malware from either a Web address or a Microsoft OneDrive account.(Citation: F-Secure The Dukes)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--800825f5-6e74-43ad-a732-476fdf471225`.
