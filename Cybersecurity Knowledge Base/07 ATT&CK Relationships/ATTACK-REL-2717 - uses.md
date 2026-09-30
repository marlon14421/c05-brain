---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0666"
target_object: "T1620"
stix_relationship_id: "relationship--28e6612e-5f92-42b0-b722-a49a43a75908"
---
# Relationship 2717: S0666 — uses → T1620

**Source object:** [[01 ATT&CK/S0666 - Gelsemium|S0666: Gelsemium]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1620 - Reflective Code Loading|T1620: Reflective Code Loading]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gelsemium](https://attack.mitre.org/software/S0666) can use custom shellcode to map embedded DLLs into memory.(Citation: ESET Gelsemium June 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--28e6612e-5f92-42b0-b722-a49a43a75908`.
