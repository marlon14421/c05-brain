---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0038"
target_object: "T1047"
stix_relationship_id: "relationship--94b4648a-4108-468c-be51-cca365fd97ac"
---
# Relationship 3553: G0038 — uses → T1047

**Source object:** [[01 ATT&CK/G0038 - Stealth Falcon|G0038: Stealth Falcon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Stealth Falcon](https://attack.mitre.org/groups/G0038) malware gathers system information via Windows Management Instrumentation (WMI).(Citation: Citizen Lab Stealth Falcon May 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--94b4648a-4108-468c-be51-cca365fd97ac`.
