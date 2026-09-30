---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0162"
target_object: "T1564.001"
stix_relationship_id: "relationship--f5acb12e-6d83-4628-9b1d-61f277a699b2"
---
# Relationship 3558: S0162 — uses → T1564.001

**Source object:** [[01 ATT&CK/S0162 - Komplex|S0162: Komplex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [Komplex](https://attack.mitre.org/software/S0162) payload is stored in a hidden directory at /Users/Shared/.local/kextd .(Citation: Sofacy Komplex Trojan)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5acb12e-6d83-4628-9b1d-61f277a699b2`.
