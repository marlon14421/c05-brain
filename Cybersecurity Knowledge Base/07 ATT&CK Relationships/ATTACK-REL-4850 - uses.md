---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0017"
target_object: "T1059.003"
stix_relationship_id: "relationship--f638cb6d-d725-444f-93f9-02f49b4d9383"
---
# Relationship 4850: S0017 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0017 - BISCUIT|S0017: BISCUIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BISCUIT](https://attack.mitre.org/software/S0017) has a command to launch a command shell on the system.(Citation: Mandiant APT1 Appendix)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f638cb6d-d725-444f-93f9-02f49b4d9383`.
