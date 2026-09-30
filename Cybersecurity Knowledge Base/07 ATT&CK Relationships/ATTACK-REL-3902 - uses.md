---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0084"
target_object: "T1027"
stix_relationship_id: "relationship--2e165a8a-928e-488e-ad16-afb77a94b460"
---
# Relationship 3902: G0084 — uses → T1027

**Source object:** [[01 ATT&CK/G0084 - Gallmaker|G0084: Gallmaker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gallmaker](https://attack.mitre.org/groups/G0084) obfuscated shellcode used during execution.(Citation: Symantec Gallmaker Oct 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2e165a8a-928e-488e-ad16-afb77a94b460`.
