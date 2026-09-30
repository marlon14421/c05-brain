---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0098"
target_object: "T1036.002"
stix_relationship_id: "relationship--8c5e20b3-b15c-4c08-84fe-eeacd9209375"
---
# Relationship 3480: G0098 — uses → T1036.002

**Source object:** [[01 ATT&CK/G0098 - BlackTech|G0098: BlackTech]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.002 - Right-to-Left Override|T1036.002: Right-to-Left Override]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BlackTech](https://attack.mitre.org/groups/G0098) has used right-to-left-override to obfuscate the filenames of malicious e-mail attachments.(Citation: TrendMicro BlackTech June 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c5e20b3-b15c-4c08-84fe-eeacd9209375`.
