---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1159"
target_object: "T1070.005"
stix_relationship_id: "relationship--b7b10c48-dd31-4b9e-a833-87f1a412e6a4"
---
# Relationship 4453: S1159 — uses → T1070.005

**Source object:** [[01 ATT&CK/S1159 - DUSTTRAP|S1159: DUSTTRAP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.005 - Network Share Connection Removal|T1070.005: Network Share Connection Removal]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DUSTTRAP](https://attack.mitre.org/software/S1159) can remove network shares from infected systems.(Citation: Google Cloud APT41 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b7b10c48-dd31-4b9e-a833-87f1a412e6a4`.
