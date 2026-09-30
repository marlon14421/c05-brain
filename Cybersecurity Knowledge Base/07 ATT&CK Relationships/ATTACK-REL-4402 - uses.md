---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "T1599"
stix_relationship_id: "relationship--50e66690-4ab2-443b-bc55-d7938a3c3f23"
---
# Relationship 4402: G0096 — uses → T1599

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1599 - Network Boundary Bridging|T1599: Network Boundary Bridging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT41](https://attack.mitre.org/groups/G0096) used `NATBypass` to bypass firewall restrictions and to access compromised systems via RDP.(Citation: apt41_dcsocytec_dec2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--50e66690-4ab2-443b-bc55-d7938a3c3f23`.
