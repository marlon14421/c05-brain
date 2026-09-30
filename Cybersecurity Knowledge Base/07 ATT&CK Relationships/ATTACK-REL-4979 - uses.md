---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0027"
target_object: "T1588.003"
stix_relationship_id: "relationship--d14513b4-9c60-49cd-88ee-0cb2ffde394a"
---
# Relationship 4979: G0027 — uses → T1588.003

**Source object:** [[01 ATT&CK/G0027 - Threat Group-3390|G0027: Threat Group-3390]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.003 - Code Signing Certificates|T1588.003: Code Signing Certificates]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Threat Group-3390](https://attack.mitre.org/groups/G0027) has obtained stolen valid certificates, including from VMProtect and the Chinese instant messaging application Youdu, for their operations.(Citation: Lunghi Iron Tiger Linux)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d14513b4-9c60-49cd-88ee-0cb2ffde394a`.
