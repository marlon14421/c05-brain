---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0279"
target_object: "T1021.005"
stix_relationship_id: "relationship--440c7f08-e570-4536-8f9c-849952581de1"
---
# Relationship 4036: S0279 — uses → T1021.005

**Source object:** [[01 ATT&CK/S0279 - Proton|S0279: Proton]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.005 - VNC|T1021.005: VNC]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Proton](https://attack.mitre.org/software/S0279) uses VNC to connect into systems.(Citation: objsee mac malware 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--440c7f08-e570-4536-8f9c-849952581de1`.
