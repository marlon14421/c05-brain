---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9008"
target_object: "T1213.003"
stix_relationship_id: "relationship--b9e23661-ec72-4e1f-8025-04e2ec12a82a"
---
# Relationship 4982: S9008 — uses → T1213.003

**Source object:** [[01 ATT&CK/S9008 - Shai-Hulud|S9008: Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1213.003 - Code Repositories|T1213.003: Code Repositories]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Shai-Hulud](https://attack.mitre.org/software/S9008) has downloaded existing packages from code repositories and extracted data stored within them.(Citation: Aikido Shai-Hulud September 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b9e23661-ec72-4e1f-8025-04e2ec12a82a`.
