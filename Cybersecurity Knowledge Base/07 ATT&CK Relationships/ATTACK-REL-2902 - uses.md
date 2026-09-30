---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1158"
target_object: "T1055.002"
stix_relationship_id: "relationship--b718fd1e-03bb-47cc-908d-22e62b029142"
---
# Relationship 2902: S1158 — uses → T1055.002

**Source object:** [[01 ATT&CK/S1158 - DUSTPAN|S1158: DUSTPAN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.002 - Portable Executable Injection|T1055.002: Portable Executable Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DUSTPAN](https://attack.mitre.org/software/S1158) can inject its decrypted payload into another process.(Citation: Google Cloud APT41 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b718fd1e-03bb-47cc-908d-22e62b029142`.
