---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0131"
target_object: "T1105"
stix_relationship_id: "relationship--fb03b86a-02d4-4079-815f-46369026ad17"
---
# Relationship 4846: G0131 — uses → T1105

**Source object:** [[01 ATT&CK/G0131 - Tonto Team|G0131: Tonto Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Tonto Team](https://attack.mitre.org/groups/G0131) has downloaded malicious DLLs which served as a [ShadowPad](https://attack.mitre.org/software/S0596) loader.(Citation: ESET Exchange Mar 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fb03b86a-02d4-4079-815f-46369026ad17`.
