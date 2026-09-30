---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0082"
target_object: "T1218.007"
stix_relationship_id: "relationship--e271f967-54d9-4466-ad16-77d001b3b0fa"
---
# Relationship 3755: G0082 — uses → T1218.007

**Source object:** [[01 ATT&CK/G0082 - APT38|G0082: APT38]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.007 - Msiexec|T1218.007: Msiexec]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT38](https://attack.mitre.org/groups/G0082) has used `msiexec.exe` to execute malicious files.(Citation: 1 - appv)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e271f967-54d9-4466-ad16-77d001b3b0fa`.
