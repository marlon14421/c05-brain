---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1084"
target_object: "T1090.002"
stix_relationship_id: "relationship--0640af26-888f-4022-ab72-2d0a69dd9bb0"
---
# Relationship 4041: S1084 — uses → T1090.002

**Source object:** [[01 ATT&CK/S1084 - QUIETEXIT|S1084: QUIETEXIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.002 - External Proxy|T1090.002: External Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[QUIETEXIT](https://attack.mitre.org/software/S1084) can proxy traffic via SOCKS.(Citation: Mandiant APT29 Eye Spy Email Nov 22)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0640af26-888f-4022-ab72-2d0a69dd9bb0`.
