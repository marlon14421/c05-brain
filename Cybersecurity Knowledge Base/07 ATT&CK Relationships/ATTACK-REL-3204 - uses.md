---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0145"
target_object: "T1547.001"
stix_relationship_id: "relationship--afa1f53f-abd9-4e57-b4e1-4e161dd34e9b"
---
# Relationship 3204: S0145 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0145 - POWERSOURCE|S0145: POWERSOURCE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[POWERSOURCE](https://attack.mitre.org/software/S0145) achieves persistence by setting a Registry Run key, with the path depending on whether the victim account has user or administrator access.(Citation: Cisco DNSMessenger March 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--afa1f53f-abd9-4e57-b4e1-4e161dd34e9b`.
