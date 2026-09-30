---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1053"
target_object: "S0359"
stix_relationship_id: "relationship--b14bb111-fcab-45fc-87cb-6b4e49270a1a"
---
# Relationship 3168: G1053 — uses → S0359

**Source object:** [[01 ATT&CK/G1053 - Storm-0501|G1053: Storm-0501]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0359 - Nltest|S0359: Nltest]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Storm-0501](https://attack.mitre.org/groups/G1053) has used Windows native utility [Nltest](https://attack.mitre.org/software/S0359), e.g. `nltest.exe`, for discovery.(Citation: Microsoft Storm-501 Sabbath Ransomware Embargo September 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b14bb111-fcab-45fc-87cb-6b4e49270a1a`.
